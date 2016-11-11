#!/usr/bin/env ruby

require 'rake/testtask'
require 'rubygems'
require 'rake'
require 'haml'

task default: :clean

task :clean do
  FileUtils.rm_r(Dir.glob("./*.html"), force: true)
end
