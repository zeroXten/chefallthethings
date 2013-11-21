Usage
=====

    $ chefallthethings myface

    ################################################################################
     Using berks to create cookbook
    ################################################################################

          create  myface/files/default
          create  myface/templates/default
          create  myface/attributes
          create  myface/definitions
          create  myface/libraries
          create  myface/providers
          create  myface/recipes
          create  myface/resources
          create  myface/recipes/default.rb
          create  myface/metadata.rb
          create  myface/LICENSE
          create  myface/README.md
          create  myface/Berksfile
          create  myface/Thorfile
          create  myface/chefignore
          create  myface/.gitignore
             run  git init from "./myface"
          create  myface/Gemfile
          create  .kitchen.yml
          append  Thorfile
          create  test/integration/default
          append  .gitignore
          append  .gitignore
          append  Gemfile
          append  Gemfile
    You must run `bundle install' to fetch any new gems.
          create  myface/Vagrantfile

    ################################################################################
     Installing required gems
    ################################################################################

    Fetching gem metadata from https://rubygems.org/.......
    Fetching gem metadata from https://rubygems.org/..
    Resolving dependencies...
    Using rake (10.1.0)
    Using i18n (0.6.5)
    Using multi_json (1.8.2)
    Using activesupport (3.2.15)
    Using addressable (2.3.5)
    Using builder (3.2.2)
    Using gyoku (1.1.0)
    Using nokogiri (1.5.10)
    Using akami (1.2.0)
    Using ast (1.1.0)
    Using buff-ruby_engine (0.1.0)
    Using buff-shell_out (0.1.1)
    Using hashie (2.0.5)
    Using chozo (0.6.1)
    Using multipart-post (1.2.0)
    Using faraday (0.8.8)
    Using minitar (0.5.4)
    Using rbzip2 (0.2.0)
    Using retryable (1.3.3)
    Using buff-extensions (0.5.0)
    Using varia_model (0.2.0)
    Using buff-config (0.4.0)
    Using buff-ignore (1.1.0)
    Using timers (1.1.0)
    Using celluloid (0.14.1)
    Using nio4r (0.5.0)
    Using celluloid-io (0.14.1)
    Using erubis (2.7.0)
    Using json (1.8.1)
    Using mixlib-log (1.6.0)
    Using mixlib-authentication (1.3.0)
    Using net-http-persistent (2.9)
    Using net-ssh (2.7.0)
    Using solve (0.8.1)
    Using ffi (1.9.3)
    Using gssapi (1.0.3)
    Using httpclient (2.3.4.1)
    Using little-plugger (1.1.3)
    Using logging (1.8.1)
    Using rubyntlm (0.1.1)
    Using rack (1.5.2)
    Using httpi (0.9.7)
    Using nori (1.1.5)
    Using wasabi (1.0.0)
    Using savon (0.9.5)
    Using uuidtools (2.1.4)
    Using winrm (1.1.3)
    Using ridley (1.5.3)
    Using thor (0.18.1)
    Using berkshelf (2.0.10)
    Using diff-lcs (1.2.5)
    Using gherkin (2.11.8)
    Installing cucumber (1.2.5)
    Using polyglot (0.3.3)
    Using treetop (1.4.15)
    Using yajl-ruby (1.1.0)
    Using foodcritic (3.0.3)
    Using mixlib-shellout (1.2.0)
    Using net-scp (1.1.2)
    Using safe_yaml (0.9.7)
    Using test-kitchen (1.0.0.beta.4)
    Using kitchen-vagrant (0.11.3)
    Using leibniz (0.2.1)
    Installing slop (3.4.7)
    Using parser (2.0.0)
    Using powerpack (0.0.9)
    Using rainbow (1.1.4)
    Using rspec-core (2.14.7)
    Using rspec-expectations (2.14.4)
    Using rspec-mocks (2.14.4)
    Using rspec (2.14.1)
    Using rubocop (0.15.0)
    Using bundler (1.3.5)
    Your bundle is complete!
    Use `bundle show [gemname]` to see where a bundled gem is installed.

    ################################################################################
     Configuring test-kitchen
    ################################################################################

       identical  .kitchen.yml

    ################################################################################
     Configuring minitest
    ################################################################################


     Done

    ################################################################################
     Configuring leibniz
    ################################################################################


     Done

    ################################################################################
     Creating Rakefile
    ################################################################################


     Done

     All done finished. Run 'cd myface; rake full' to start full test suite.

What it creates
---------------

    $ cd myface/
    myface$ tree
    .
    ├── Berksfile
    ├── Gemfile
    ├── Gemfile.lock
    ├── LICENSE
    ├── README.md
    ├── Rakefile
    ├── Thorfile
    ├── Vagrantfile
    ├── attributes
    ├── chefignore
    ├── definitions
    ├── features
    │   ├── myface.feature
    │   ├── step_definitions
    │   │   └── myface_steps.rb
    │   └── support
    │       └── env.rb
    ├── files
    │   └── default
    │       └── test
    │           └── default_test.rb
    ├── libraries
    ├── metadata.rb
    ├── providers
    ├── recipes
    │   └── default.rb
    ├── resources
    ├── templates
    │   └── default
    └── test
        └── integration
            └── default

    17 directories, 15 files

Rake tasks
----------

 * rake lint
 * rake test
 * rake spec
 * rake full
