require 'albacore'
build :msbuild do |b|
  b.properties = { :configuration => :Debug }
  b.target = [ 'Clean', 'Build' ]
  b.file = "WillsDemoCFTemplate.sln"
  b.logging = 'detailed'
end
