use_relative_paths = True

vars = {
  'github': 'https://github.com',

  'abseil_revision': '8fb9488890264bcb4f468604b84f2e301b2cd61f',

  'effcee_revision': 'f8e8a164822d4f65e757bff66bc00e1567959aa0',

  'googletest_revision': 'cd8e73f067129f8489e35c7b51c7a68552b289d2',

  # Use protobufs before they gained the dependency on abseil
  'protobuf_revision': 'v21.12',

  're2_revision': '2da0056814cf180480a19f5cf811e7e1c054bf6d',

  'spirv_headers_revision': 'fbf86836a9b1966586faf7be7bb8a6440e156d62',
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
