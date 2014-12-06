require 'hoe'
require './lib/sportdb/version.rb'


Hoe.spec 'sportdb-models' do

  self.version = SportDb::VERSION

  self.summary = "sportdb-models - sport.db schema 'n' models for easy (re)use"
  self.description = summary

  self.urls    = ['https://github.com/sportdb/sport.db.models']

  self.author  = 'Gerald Bauer'
  self.email   = 'opensport@googlegroups.com'

  # switch extension to .markdown for gihub formatting
  #  -- NB: auto-changed when included in manifest
  self.readme_file  = 'README.md'
  self.history_file = 'HISTORY.md'

  self.extra_deps = [
    ['worlddb-models', '>= 2.1.0'],    # Note: pull in all (extra) dependencies va worlddb-models
    ['persondb-models', '>= 0.4.2'],     # persons (people) table
  ]

  self.licenses = ['Public Domain']

  self.spec_extras = {
    required_ruby_version: '>= 1.9.2'
  }

end

