require "rake"
task :default => ["all_together_now"]

task :tests do
    puts "totally need some tests here."
  end
 
  task :build do
    puts "Created boilerplate stuff."
    puts "Padded out with guff."
    puts "But thankfully got the build to go green."
  end
 
  task :verify do
    tests = ENV["TEST_SCENARIOS"] || 1
    puts "Created #{tests} test(s). Trust levels are still low."
  end
 
  task :all_together_now => [:tests, :build, :verify] do
    puts "Ready for LIVE!"
  end
