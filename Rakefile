desc 'host the site'
task :host do
  sh "budo -d docs"
end

desc 'build the site'
task :build do
  sh "ruby build_01.rb docs/src/01.csv > docs/sdgs01_beta.html"
  sh "ruby build_02.rb docs/src/02.csv > docs/sdgs02_beta.html"
  sh "ruby build_03.rb docs/src/03.csv > docs/sdgs03_beta.html"
  sh "ruby build_04.rb docs/src/04.csv > docs/sdgs04_beta.html"
  sh "ruby build_05.rb docs/src/05.csv > docs/sdgs05_beta.html"
  sh "ruby build_06.rb docs/src/06.csv > docs/sdgs06_beta.html"
  sh "ruby build_07.rb docs/src/07.csv > docs/sdgs07_beta.html"
  sh "ruby build_08.rb docs/src/08.csv > docs/sdgs08_beta.html"
  sh "ruby build_09.rb docs/src/09.csv > docs/sdgs09_beta.html"
  sh "ruby build_10.rb docs/src/10.csv > docs/sdgs10_beta.html"
  sh "ruby build_11.rb docs/src/11.csv > docs/sdgs11_beta.html"
  sh "ruby build_12.rb docs/src/12.csv > docs/sdgs12_beta.html"
  sh "ruby build_13.rb docs/src/13.csv > docs/sdgs13_beta.html"
  sh "ruby build_14.rb docs/src/14.csv > docs/sdgs14_beta.html"
  sh "ruby build_15.rb docs/src/15.csv > docs/sdgs15_beta.html"
  sh "ruby build_16.rb docs/src/16.csv > docs/sdgs16_beta.html"
end
