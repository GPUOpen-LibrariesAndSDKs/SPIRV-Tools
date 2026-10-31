use_relative_paths = True

vars = {
  'github': 'https://github.com',

  'abseil_revision': '8ca2addca1c4011b6161671dfa89066e7108425f',

  'effcee_revision': '05be15d8a2b985a3ffee004a5e1fcea8a0528d0a',

  'googletest_revision': 'a8380b01a25ebdb130097b607b3afed2a58d04ba',

  # Use protobufs before they gained the dependency on abseil
  'protobuf_revision': 'v21.12',

  're2_revision': '2da0056814cf180480a19f5cf811e7e1c054bf6d',

  'spirv_headers_revision': 'fef168c54ed2e37c314eb251806aaf9877f38465',
}

deps = {
  'external/abseil_cpp':
      Var('github') + '/abseil/abseil-cpp.git@' + Var('abseil_revision'),

  'external/effcee':
      Var('github') + '/google/effcee.git@' + Var('effcee_revision'),

  'external/googletest':
      Var('github') + '/google/googletest.git@' + Var('googletest_revision'),

  'external/protobuf':
      Var('github') + '/protocolbuffers/protobuf.git@' + Var('protobuf_revision'),

  'external/re2':
      Var('github') + '/google/re2.git@' + Var('re2_revision'),

  'external/spirv-headers':
      Var('github') +  '/KhronosGroup/SPIRV-Headers.git@' +
          Var('spirv_headers_revision'),
}
