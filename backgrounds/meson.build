dataconf = configuration_data()
dataconf.set('BACKGROUNDDIR', backgrounddir)
dataconf.set('datadir', datadir)

backgrounds = ['vanilla-default.svg',  'vanilla-dark.svg', 'better-soft.webp', 'better-neon.webp', 'impellent-light.webp', 'impellent-dark.webp', 'orchid-light.svg', 'orchid-dark.svg']

install_data(backgrounds, install_dir: backgrounddir)

configure_file(input: 'vanilla.xml.in',
    output: 'vanilla.xml',
    configuration: dataconf,
    install: true,
    install_dir: metadatadir
  )
