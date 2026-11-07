use_relative_paths = True

vars = {
  'github': 'https://github.com',

  'abseil_revision': 'b652a9f424a1ceeaa86efb77bc7c6c1cab84a2f8',

  'effcee_revision': '05be15d8a2b985a3ffee004a5e1fcea8a0528d0a',

  'googletest_revision': '6450691fd7d07ef932582206fbafb1a513927e08',

  # Use protobufs before they gained the dependency on abseil
  'protobuf_revision': 'v21.12',

  're2_revision': '2da0056814cf180480a19f5cf811e7e1c054bf6d',

  'spirv_headers_revision': '6efe5ae6b7c6ad29da3f2cc3f164b9c3d72b78b1',
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
