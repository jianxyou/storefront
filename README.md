# storefront


A django backend-project, practiced Apis development, and some advanced Api concepts.

 RESTful Apis

 Generic views

 Model viewset
  
 authentication system
 
 securing Api
 
 
## The main code is in the following files:

### 1, store.models.py
models a store's collections, products, customers, and orders, also include Meta classes for ordering and permissions. The app also uses the built-in Django admin interface to display and manage the data in the models.

### 2, store.serializers.py
contains a number of serializers for various models used in a Django application, and convert complex data types such as querysets and model instances into JSON, XML or other formats.

### 3, store.urls.py
define a set of URL patterns for the application, and how they should be mapped to views. The file uses the routers provided by the rest_framework_nested package to automatically generate the URLs for various viewsets.

### 4, store.views.py
contains viewsets for various models used in a Django application. Viewsets are used to handle HTTP requests and return HTTP responses for a specific model or queryset. The file contains viewsets for the following models: Product, Collection, Review, Cart, and CartItem.
