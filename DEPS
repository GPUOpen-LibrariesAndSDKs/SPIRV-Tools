use_relative_paths = True

vars = {
  'github': 'https://github.com',

  'abseil_revision': '4ed4598af355d5405c26f12f605cd093b7ce2c00',

  'effcee_revision': 'f8e8a164822d4f65e757bff66bc00e1567959aa0',

  'googletest_revision': '8eff9e336692fc95961e096564f1044c600b881d',

  # Use protobufs before they gained the dependency on abseil
  'protobuf_revision': 'v21.12',

  're2_revision': '972a15cedd008d846f1a39b2e88ce48d7f166cbd',

  'spirv_headers_revision': '04fd3caa1e8267e4d95c806cad901181728e1006',
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
