scala_library(name='scala',
  provides = scala_artifact(
    org = 'com.twitter',
    name = 'finagle-stats',
    repo = artifactory,
  ),
  dependencies=[
    '3rdparty:jackson-core',
    '3rdparty:jackson-databind',
    '3rdparty:jackson-module-scala',
    '3rdparty:netty',
    '3rdparty/jvm/com/twitter/common:metrics',
    'finagle/finagle-core',
    'finagle/finagle-http',
    'util/util-core',
  ],
  sources=rglobs('*.scala'),
  resources=[
    'finagle/finagle-stats/src/main/resources'
  ],
)
