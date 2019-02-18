require 'test/unit/assertions'

class MyTest
	include Test::Unit::Assertions

	def test!
		assert(false, "expected false to be .. not false?")
	end
end

task :test do
	MyTest.new.test!
end

task default: ["test"]
