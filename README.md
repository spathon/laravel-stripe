# A minimal Laravel 5 package for Stripe PHP API ~3.1

### Installation 
* Add `"spathon/laravel-stripe": "~1.0"` to **composer.json**
* Run `composer update`
* Add `Spathon\LaravelStripe\LaravelStripeServiceProvider::class` to providers in **config/app.php**
* Set the stripe secret in **config/services.php** ( use .env for this )


### Usage
All this package is doing is setting the Stripe secret key so you can use the Stripe SDK anywhere anytime.


#### Why?
I created this package mostly to learn how to make a package.
Most stripe packages was for L4
