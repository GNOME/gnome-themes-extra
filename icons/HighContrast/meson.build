install_subdir('16x16',
  install_dir: join_paths(icondir, 'HighContrast')
)
install_subdir('22x22',
  install_dir: join_paths(icondir, 'HighContrast')
)
install_subdir('24x24',
  install_dir: join_paths(icondir, 'HighContrast')
)
install_subdir('256x256',
  install_dir: join_paths(icondir, 'HighContrast')
)
install_subdir('32x32',
  install_dir: join_paths(icondir, 'HighContrast')
)
install_subdir('48x48',
  install_dir: join_paths(icondir, 'HighContrast'),
  exclude_files: ['animations/process-working.xcf'],
)
install_subdir('scalable',
  install_dir: join_paths(icondir, 'HighContrast'),
  exclude_files: ['mimetypes/text-x-preview.icon'],
)

i18n.merge_file(
  input: 'index.theme.in',
  output: 'index.theme',
  type: 'desktop',
  po_dir: po_dir,
  install: true,
  install_dir: join_paths(icondir, 'HighContrast')
)
