gmodule_dep = dependency('gmodule-2.0')
gtk_dep = dependency('gtk+-2.0')
gtk_binary_version = gtk_dep.get_pkgconfig_variable('gtk_binary_version')
shared_module('adwaita',
  ['adwaita_engine.c'],
  dependencies: [ gmodule_dep, gtk_dep ],
  install: true,
  install_dir: join_paths(get_option('libdir'), 'gtk-2.0', gtk_binary_version, 'engines')
)
