source 'https://rubygems.org'

gem 'jekyll'

# Core plugins that directly affect site building
group :jekyll_plugins do
    gem 'jekyll-3rd-party-libraries'
    gem 'jekyll-cache-bust'
    gem 'jekyll-feed'
    gem 'jekyll-link-attributes'
    gem 'jekyll-minifier'
    gem 'jekyll-regex-replace'
    gem 'jekyll-scholar'
    gem 'jekyll-sitemap'
    gem 'jekyll-terser', :git => "https://github.com/RobertoJBeltran/jekyll-terser.git"
end

# Gems that the plugins above need but do not install themselves
group :other_plugins do
    gem 'css_parser'     # used by jekyll-3rd-party-libraries
    gem 'observer'       # used by jekyll-scholar
end

# Gems for al-folio plugins
group :al_folio_plugins do
    gem 'al_folio_core', '= 1.0.15'
    gem 'al_icons', '= 1.0.0'
    gem 'al_folio_upgrade', '= 1.0.3'
    gem 'al_citations', '= 1.0.1'
end
