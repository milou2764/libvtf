sources = [
  'Error.cpp',
  'FileReader.cpp',
  'FileWriter.cpp',
  'Float16.cpp',
  'MemoryReader.cpp',
  'MemoryWriter.cpp',
  'Proc.cpp',
  'ProcReader.cpp',
  'ProcWriter.cpp',
  'VMTFile.cpp',
  'VMTGroupNode.cpp',
  'VMTIntegerNode.cpp',
  'VMTNode.cpp',
  'VMTSingleNode.cpp',
  'VMTStringNode.cpp',
  'VMTValueNode.cpp',
  'VMTWrapper.cpp',
  'VTFFile.cpp',
  'VTFLib.cpp',
  'VTFMathlib.cpp',
  'VTFWrapper.cpp',
]

deps = [
  dependency('IL'),
]

libvtf_lib = static_library('vtf', sources,
  dependencies: deps,
)
libvtf_dep = declare_dependency(
  link_with: libvtf_lib,
  include_directories: libvtf_include,
)