use_relative_paths = True

vars = {
  'github': 'https://github.com',

  'abseil_revision': '2d5a8e38e7443d0aef7c5fe4a3590fbaa44e8978',

  'effcee_revision': 'f8e8a164822d4f65e757bff66bc00e1567959aa0',

  'googletest_revision': '4267679b6887f349f17b01ccd70c9e3483689b25',

  # Use protobufs before they gained the dependency on abseil
  'protobuf_revision': 'v21.12',

  're2_revision': '972a15cedd008d846f1a39b2e88ce48d7f166cbd',

  'spirv_headers_revision': '2b7475f6d664efbad4d4315c94ecec9640831e5b',
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
