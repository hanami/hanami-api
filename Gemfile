# frozen_string_literal: true

source "https://rubygems.org"
gemspec

gem "byebug", require: false
gem "hanami-router", github: "hanami/router"

if ENV["RACK_VERSION_CONSTRAINT"]
  gem "rack", ENV["RACK_VERSION_CONSTRAINT"]
end
