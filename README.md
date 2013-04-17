# RackProf

Rack middleware for profiling.

## Installation

    gem 'rack_prof'

or

    $ gem install rack_prof

## Usage

Modify `config.ru` like:

    use RackProf

    require ::File.expand_path('../config/environment',  __FILE__)
    run YourApp::Application

## Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request
