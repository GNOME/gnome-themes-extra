subdir('gtk-2.0')
subdir('gtk-3.0')

i18n.merge_file(
  input: 'index.theme.in',
  output: 'index.theme',
  type: 'desktop',
  po_dir: po_dir,
  install: true,
  install_dir: join_paths(themedir, 'Adwaita'),
)
