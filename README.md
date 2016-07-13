# install a bunch of PNG tools on mac

pngcrush
    
    cd pngcrush-1.8.1
    make
    sudo mv pngcrush /usr/local/bin/
    
pngout
    
    cd pngout-20150920-darwin
    make
    sudo mv pngout /usr/local/bin/
    
optipng

    brew install opting
    
advdef, advpng......

    cd advancecomp-1.20
    sudo ./configure
    sudo make install
    
jpegoptim

    brew install jpegoptim

