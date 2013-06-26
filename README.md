# Sinatra + Haml + Foundation

<p align="center">
  <img src="http://openiconlibrary.sourceforge.net/gallery2/open_icon_library-full/icons/png/256x256/symbols/pictogram-din-w000-general.png"/>
</p>
<p align="center">
  this project is currenty **not** in a working state
</p>

##Main components of project

####Sinatra
- Sinatra [site](http://www.sinatrarb.com/)

####Haml
- Haml [site](http://haml.info/)

####Foundation
- Foundation [site](http://foundation.zurb.com)
- Documentation is available [here](http://foundation.zurb.com/docs/)


#### Setup
All of the example projects and the bare bones project are set up with:
    - Bundler
    - Shotgun
    - Rack
    - Haml
    - Vlad the Deployer

To get up and running all that should be needed is to install the Ruby gem
Bundler if up don't already have it installed then run:
    
    $ bundle install

  That should install everything that is need for the app to run. To start it run:
    
    
    $ shotgun
    

Update the config.ru file to change Shotgun settings. Likewise /config/deploy.rb for the Vlad settings and
Gemfile for your bundler install settings

## Credits

Forked from the sweet [sinatra+haml+bootstrap](https://github.com/ghostandthemachine/sinatra-haml-bootstrap-fluid) project by [ghostandthemachine](https://github.com/ghostandthemachine)
