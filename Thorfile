require 'rubygems'
require 'bundler/setup'

require 'term/ansicolor'

class Rcfiles < Thor
  include Thor::Actions
  include Term::ANSIColor
  Term::ANSIColor.escaped=true

  source_root File.dirname(__FILE__)

  desc "install", "them"
  def install
    template("templates/bashrc.erb", "bashrc")
  end


end
