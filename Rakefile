# -*- coding: utf-8 -*-
$:.unshift("/Library/RubyMotion/lib")
require 'motion/project/template/ios'

begin
  require 'bundler'
  Bundler.require
rescue LoadError
end

ENV['device_name'] ||= 'iPhone 5'
Motion::Project::App.setup do |app|
  # Use `rake config' to see complete project settings.
  app.name = 'Magic 8-Ball'
  app.icons << 'icon.png'
end
