# frozen_string_literal: true

require "bundler/gem_tasks"
require "rake/testtask"
require "rake/extensiontask"

Rake::ExtensionTask.new("mkxp_z") do |ext|
  ext.lib_dir = "lib/mkxp_z"
end

task default: %i[test rubocop]
