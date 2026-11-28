use_relative_paths = True

vars = {
  'github': 'https://github.com',

  'abseil_revision': '476c5e0d491c80cd7d58dd62d6c7bb76b230e679',

  'effcee_revision': '05be15d8a2b985a3ffee004a5e1fcea8a0528d0a',

  'googletest_revision': 'a46a6012a133c7c0929fdae55b321c2fe65f3c5f',

  # Use protobufs before they gained the dependency on abseil
  'protobuf_revision': 'v21.12',

  're2_revision': '2da0056814cf180480a19f5cf811e7e1c054bf6d',

  'spirv_headers_revision': 'f6f78c717057ac7f5f3ea021f3f962aaf9d4da7e',
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
