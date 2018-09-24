project(
  'gnome-themes-extra', 'c',
  version: '3.28',
  license: 'GPL2+',
  default_options: 'buildtype=debugoptimized',
  meson_version: '>= 0.48'
)

i18n = import('i18n')

icondir  = join_paths(get_option('datadir'), 'icons')
themedir = join_paths(get_option('datadir'), 'themes')
po_dir   = join_paths(meson.source_root(), 'po')

subdir('po')
subdir('icons')
subdir('themes')
if get_option('adwaita-engine')
  subdir('src')
endif
