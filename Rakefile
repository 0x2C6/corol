$: << './lib'
require 'corol'
desc "Test colors and compatibility"
task :test do 
puts <<NOTE
This is the ruby file for color testing . You can learn all colors and its method names . Just run this ruby file.
Please note that some colors may not work on some colsoles.
NOTE
puts  "############################################"
Corol.public_instance_methods.each do |method|
  print "Method for this color ".method(method).call,"= .#{method}\n"
end
end
