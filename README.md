# Awesome RSpec [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of awesome RSpec-related resources

## Contents
- [RSpec](#rspec)
- [Style guides and linters](#style-guides-and-linters)
- [Books](#books)
- [Matchers](#matchers)
- [Mocks](#mocks)
- [Parallel execution](#parallel-execution)
- [Tools](#tools)

## RSpec
- [RSpec official web site](https://rspec.info)

## Style guides and linters
- [RSpec Style Guide](https://rspec.rubystyle.guide)
- [rubocop-rspec](https://github.com/rubocop/rubocop-rspec)
- [rubocop-factory_bot](https://github.com/rubocop/rubocop-factory_bot)

## Books
- [Effective testing with RSpec 3](https://pragprog.com/titles/rspec3/effective-testing-with-rspec-3/)
- [Everyday Rails Testing with RSpec](https://leanpub.com/everydayrailsrspec)

## Matchers
- [rspec-any_of](https://github.com/toptal/rspec-any_of) - Provides `any_of` and `all_of` matchers.
- [action_mailer_matchers](https://github.com/contently/action_mailer_matchers) - RSpec matchers to test Rails' common ActionMailer functionality.
- [active_record_block_matchers](https://github.com/nwallace/active_record_block_matchers) - Custom RSpec matchers for ActiveRecord record creation.
- [db-query-matchers](https://github.com/sds/db-query-matchers) - RSpec matchers for database queries made by ActiveRecord.
- [mongoid-rspec](https://github.com/mongoid/mongoid-rspec) - RSpec matchers for Mongoid.
- [human_time](https://github.com/allenan/human_time) - Time and date comparisons for humans.
- [n_plus_one_control](https://github.com/palkan/n_plus_one_control) - Matchers to ensure code doesn't produce N+1 queries.
- [pundit-matchers](https://github.com/pundit-community/pundit-matchers) - A set of RSpec matchers for testing Pundit authorisation policies.
- [resque_spec](https://github.com/leshill/resque_spec) - A test double of Resque for RSpec.
- [rspec-graphql_matchers](https://github.com/khamusa/rspec-graphql_matchers) - GraphQL matchers.
- [rspec-json_matchers](https://github.com/PikachuEXE/rspec-json_matchers) - A collection of RSpec matchers for testing JSON data.
- [rspec-benchmark](https://github.com/piotrmurach/rspec-benchmark) - Performance testing matchers for RSpec.
- [rspec-sidekiq](https://github.com/wspurgin/rspec-sidekiq) - Simple testing of Sidekiq jobs via a collection of matchers and helpers.
- [rspec-sqlimit](https://github.com/nepalez/rspec-sqlimit) - RSpec matcher to control SQL queries made by block of code.
- [shoulda-matchers](https://github.com/thoughtbot/shoulda-matchers) - One-liners to test common Rails functionality.

## Mocks
- [active_mocker](https://github.com/zeisler/active_mocker) - Creates stub classes from any ActiveRecord model.
- [bunny-mock](https://github.com/arempe93/bunny-mock) - A mock client for RabbitMQ modeled after the Bunny client in ruby.
- [mock_redis](https://github.com/sds/mock_redis) -MockRedis provides the same interface as redis-rb, but it stores its data in memory instead of talking to a Redis server.
- [mock5](https://github.com/rwz/mock5) - Create and manage API mocks with Sinatra.
- [moctail](https://github.com/testdouble/mocktail) - A mocking library for Ruby built with modern Ruby 3 APIs and with first-class support for type checking with Sorbet.
- [mosoco](https://github.com/frodsan/mocoso) - A minimalist stub & mock library.
- [rspec-stubbed_env](https://github.com/pboling/rspec-stubbed_env/) - Simple helper method to stub ENV values within RSpec tests.
- [resque-mock](https://github.com/danp/resque-mock) - Resque mocking without redis.
- [ruby-dns-mock](https://github.com/mocktools/ruby-dns-mock) - Mimic any DNS records for your test environment with fake DNS server.
- [ruby-smtp-mock](https://github.com/mocktools/ruby-smtp-mock) - Mimic any SMTP server behaviour for your test environment with fake SMTP server.
- [spy](https://github.com/ryanong/spy) - A simple opinionated mocking framework.
- [stripe-ruby-mock](https://github.com/stripe-ruby-mock/stripe-ruby-mock) - A mocking library for testing Stripe integration.
- [stub_shell](https://github.com/stackbuilders/stub_shell/) - Helps you to test your libraries that interact with the system through the Kernel backquote and system methods.
- [testftpd](https://github.com/christian-schulze/testftpd) - Simple FTP server written in pure Ruby, allowing integration testing of FTP client code without mocks and stubs.
- [verified_double](https://github.com/gsmendoza/verified_double) - Contract tests for mocks.

## Parallel execution
- [flatware](https://github.com/briandunn/flatware) - A parallel test runner for RSpec and Cucumber with pretty output.
- [knapsack](https://github.com/KnapsackPro/knapsack) - Knapsack splits tests evenly across parallel CI nodes to run fast CI build and save you time.
- [parallel_tests](https://github.com/grosser/parallel_tests) - Speedup tests by running parallel on multiple CPU cores.
- [rspecq](https://github.com/skroutz/rspecq) - Distribute and run RSpec suites among parallel workers; for faster CI builds.
- [test-queue](https://github.com/tmm1/test-queue) - Parallel test runner for CI environments

## Tools
- [chefspec](https://github.com/chefspec/chefspec) - Write RSpec examples and generate coverage reports for Chef recipes.
- [crystallball](https://github.com/toptal/crystalball) - Regression Test Selection library for your RSpec test suite.
- [database_cleaner](https://github.com/DatabaseCleaner/database_cleaner) - Strategies for cleaning databases in Ruby. Can be used to ensure a clean state for testing.
- [database_rewinder](https://github.com/amatsuda/database_rewinder) - Minimalist and ultra-fast database cleaner.
- [dockerspec](https://github.com/zuazo/dockerspec) - A small Ruby Gem to run RSpec and Serverspec, Infrataster and Capybara tests against Dockerfiles or Docker images easily.
- [factory_bot](https://github.com/thoughtbot/factory_bot) - A library for building database records.
- [factory_trace](https://github.com/djezzzl/factory_trace) - Simple tool to maintain factories and traits from FactoryBot.
- [mutant](https://github.com/mbj/mutant) - Mutation testing.
- [rspectre](https://github.com/dgollahon/rspectre) - Tool to remove unused parts of the specs.
- [rspec_tracer](https://github.com/avmnu-sng/rspec-tracer) - RSpec Tracer is a specs dependency analyzer, flaky tests detector, tests accelerator, and coverage reporter tool.
- [super-diff](https://github.com/mcmire/super_diff) - A more helpful way to view differences between complex data structures in RSpec.
- [test-prof](https://github.com/test-prof/test-prof) - Tools to analyze test suite performance +helpers to write faster tests.
- [vcr](https://github.com/vcr/vcr) - Record your test suite's HTTP interactions and replay them during future test runs for fast, deterministic, accurate tests.
- [with_model](https://github.com/Casecommons/with_model) - Dynamically build an Active Record model (with table) within a test context.
- [yardspec](https://github.com/r7kamura/yardspec) Run RSpec examples embedded in yard
