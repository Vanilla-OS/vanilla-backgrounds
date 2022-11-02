dataconf = configuration_data()
dataconf.set('BACKGROUNDDIR', backgrounddir)
dataconf.set('datadir', datadir)

backgrounds = ['vanilla-default.webp',  'vanilla-dark.webp']

install_data(backgrounds, install_dir: backgrounddir)

configure_file(input: 'vanilla.xml.in',
    output: 'vanilla.xml',
    configuration: dataconf,
    install: true,
    install_dir: metadatadir
  )
