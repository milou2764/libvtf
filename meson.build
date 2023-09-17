project('libvtf', ['cpp', 'c'],
          version: '0.1.0',
    meson_version: '>= 0.62.0',
  default_options: [ 'warning_level=2', 'werror=false', 'cpp_std=gnu++2a' ],
)

if not meson.is_subproject()
  message('WARNING: This project is only intended to be used as a subproject!')
endif

subdir('lib')
subdir('VTFLib')
subdir('VTFCmd')