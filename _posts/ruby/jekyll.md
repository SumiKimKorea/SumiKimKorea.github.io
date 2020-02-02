Traceback (most recent call last):
        2: from C:/Ruby26-x64/bin/jekyll:23:in `<main>'
        1: from C:/Ruby26-x64/lib/ruby/gems/2.6.0/gems/bundler-2.1.4/lib/bundler/rubygems_integration.rb:402:in `block in replace_bin_path'
C:/Ruby26-x64/lib/ruby/gems/2.6.0/gems/bundler-2.1.4/lib/bundler/rubygems_integration.rb:374:in `block in replace_bin_path': can't find executable jekyll for gem jekyll. jekyll is not currently included in the bundle, perhaps you meant to add it to your Gemfile? (Gem::Exception)

bundler 버전과 시스템에 설치된 bundler 버전이 맞지 않아서이다.
Gemfile.lock 파일을 삭제한다.

jekyll -v 
Warning: the running version of Bundler (2.1.2) is older than the version that created the lockfile (2.1.4). We suggest you to upgrade to the version that created the lockfile by running `gem install bundler:2.1.4`.
jekyll 4.0.0