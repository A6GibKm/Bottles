pkgdatadir = join_paths(get_option('prefix'), get_option('datadir'), meson.project_name())
winedir = join_paths(pkgdatadir, 'bottles/backend/wine')

bottles_sources = [
  '__init__.py',
  'catalogs.py',
  'winecommand.py',
  'wineprogram.py',
  'uninstaller.py',
  'winecfg.py',
  'winedbg.py',
  'wineserver.py',
  'wineboot.py',
  'cmd.py',
  'taskmgr.py',
  'control.py',
  'regedit.py',
  'reg.py',
  'regkeys.py',
  'net.py',
  'msiexec.py',
  'executor.py',
  'start.py',
  'register.py',
  'winebridge.py',
  'explorer.py',
  'drives.py',
]

install_data(bottles_sources, install_dir: winedir)
