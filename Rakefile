task :clean do
	system "rm -rf _site/"
end

task :serve do
	system "jekyll serve"
end

task :build do
	system "jekyll build"
end

task :deploy do
	system "s3_website push"
end