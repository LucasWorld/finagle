scala_library(
  provides = scala_artifact(
    org = 'com.twitter',
    name = 'finagle-serversets',
    repo = artifactory,
  ),
  dependencies=[
    '3rdparty/jvm/com/fasterxml/jackson/core:jackson-databind',
    '3rdparty/jvm/com/github/ben-manes/caffeine',
    '3rdparty/jvm/com/google/guava:guava',
    '3rdparty/jvm/com/google/inject:guice',
    '3rdparty/jvm/org/apache/thrift:libthrift-0.5.0',
    '3rdparty/jvm/org/apache/zookeeper:zookeeper-client',
    'finagle/finagle-core/src/main/scala:scala',
    'finagle/finagle-serversets/src/main/resources',
    'finagle/finagle-serversets/src/main/java',
    'finagle/finagle-serversets/src/main/thrift:thrift-java',
    'util/util-app/src/main/scala:scala',
    'util/util-cache',
    'util/util-core/src/main/scala:scala',
    'util/util-logging/src/main/scala:scala',
    'util/util-stats/src/main/scala:scala',
  ],
  sources=rglobs('*.scala'),
  # Exposes a service-loaded class.
  scope='forced',
  strict_deps=True,
)
