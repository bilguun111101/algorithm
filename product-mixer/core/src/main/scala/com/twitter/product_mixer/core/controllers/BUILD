scala_library(
    sources = ["*.scala"],
    compiler_option_sets = ["fatal_warnings"],
    platform = "java8",
    strict_deps = True,
    tags = ["bazel-compatible"],
    dependencies = [
        "3rdparty/jvm/com/twitter/bijection:core",
        "3rdparty/jvm/javax/inject:javax.inject",
        "finagle/finagle-thriftmux/src/main/scala",
        "finatra-internal/mtls-thriftmux/src/main/scala",
        "finatra/http-server/src/main/scala/com/twitter/finatra/http",
        "product-mixer/core/src/main/scala/com/twitter/product_mixer/core/functional_component/common/access_policy",
        "product-mixer/core/src/main/scala/com/twitter/product_mixer/core/functional_component/common/alert",
        "product-mixer/core/src/main/scala/com/twitter/product_mixer/core/model/marshalling/request",
        "product-mixer/core/src/main/scala/com/twitter/product_mixer/core/module/product_mixer_flags",
        "product-mixer/core/src/main/scala/com/twitter/product_mixer/core/pipeline/mixer",
        "product-mixer/core/src/main/scala/com/twitter/product_mixer/core/pipeline/product",
        "product-mixer/core/src/main/scala/com/twitter/product_mixer/core/pipeline/recommendation",
        "product-mixer/core/src/main/scala/com/twitter/product_mixer/core/service/component_registry",
        "scrooge-internal/scrooge-schema/src/main/scala/com/twitter/scrooge/schema",
        "scrooge-internal/scrooge-schema/src/main/scala/com/twitter/scrooge/schema/json",
        "scrooge-internal/scrooge-schema/src/main/scala/com/twitter/scrooge/schema/scrooge/scala",
        "scrooge-internal/scrooge-schema/src/main/scala/com/twitter/scrooge/schema/serialization/thrift",
        "scrooge-internal/scrooge-schema/src/main/scala/com/twitter/scrooge/schema/tree",
        "scrooge/scrooge-core/src/main/scala",
        "scrooge/scrooge-generator/src/main/scala",
        "scrooge/scrooge-serializer",
        "src/thrift/com/twitter/context:twitter-context-scala",
        "src/thrift/com/twitter/scrooge_internal/schema:thrift-scala",
        "twitter-context/src/main/scala",
    ],
    exports = [
        "product-mixer/core/src/main/scala/com/twitter/product_mixer/core/functional_component/common/access_policy",
        "product-mixer/core/src/main/scala/com/twitter/product_mixer/core/model/marshalling/request",
        "src/thrift/com/twitter/context:twitter-context-scala",
        "twitter-context/src/main/scala",
    ],
)
