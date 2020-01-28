test('decodetree', files('decode/check.sh'),
     args: [ config_host['PYTHON'], files('../scripts/decodetree.py') ],
     workdir: meson.current_source_dir() / 'decode',
     suite: 'decodetree')

if 'CONFIG_TCG' in config_host
  subdir('fp')
endif

subdir('qapi-schema')
