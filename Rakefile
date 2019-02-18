require 'test/unit/assertions'

class MyTest
	include Test::Unit::Assertions

	def test!
		assert(true, "sanity check")
	end
end

task :test do
	MyTest.new.test!
end

task default: ["test"]
