# edamam-url.github.io
# Require Edamam URL for Skillcrush practice


require 'http'
 
result = HTTP.get('https://www.edamam.com/search?type=Feeds').to_s
result
