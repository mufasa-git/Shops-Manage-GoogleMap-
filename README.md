# Laravel Simple Shops Map with Google Maps API with Adminpanel

## Features

- __Adminpanel__ with administrator user managing shops and categories
- __Registration__ for shop owners who can manage their own shops - with __multi-tenancy__ included
- Adminpanel uses Google Places API with autocomplete to __automatically get coordinates from address__
- Adminpanel uses [Spatie Opening Hours package](https://github.com/spatie/opening-hours) to manage working hours
- Front-end uses Google Maps API to __view the map of shops__


## How to use

- Clone the repository with __git clone__
- Copy __.env.example__ file to __.env__ and edit database credentials there
- Run __composer install__
- Run __php artisan key:generate__
- Run __php artisan migrate --seed__ (it has some seeded data for your testing)
- In your __.env__ file add your Google Maps API key: `GOOGLE_MAPS_API_KEY=AIzaSyBi2dVBkdQSUcV8_xxxxxxxxxxxx`
- That's it: launch the main URL. 
- You can login to adminpanel by going go `/login` URL and login with credentials __admin@admin.com__ - __password__
- Click __Register__ on top right to add new shop owner and their shops


