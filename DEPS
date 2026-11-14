use_relative_paths = True

vars = {
  'github': 'https://github.com',

  'abseil_revision': 'be93ce230ef75c5e57366c500e71cac4f4f4241a',

  'effcee_revision': '05be15d8a2b985a3ffee004a5e1fcea8a0528d0a',

  'googletest_revision': 'e882c36410197464e3429546e6a7d5e217bde51e',

  # Use protobufs before they gained the dependency on abseil
  'protobuf_revision': 'v21.12',

  're2_revision': '2da0056814cf180480a19f5cf811e7e1c054bf6d',

  'spirv_headers_revision': '5c6004e758e0c80185ef2cee93ae5c10fa342a5b',
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
