source('https://rubygems.org')

gem('sinatra')
gem('sinatra-contrib')

get('/form') do
  erb(:form)
end

get('/story')
  @person1 = params.fetch('person1')
  @person2 = params.fetch('person2')
  @animal = params.fetch('animal')
  @exclamation = params.fetch('exclamation')
  @verb = params.fetch('verb')
  @noun = params.fetch('noun')
  erb(:story)
end
