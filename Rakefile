desc 'create style.json'
task :style do
  sh "parse-hocon conf/style.conf > docs/style.json"
  sh "gl-style-validate docs/style.json"
end

desc 'host the site locally'
task :host do
  sh "budo -d docs"
end

