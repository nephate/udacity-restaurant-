# udacity-restaurant-
window.initMap = () => { let loc = { lat: 40.722216, lng: -73.987501 }; self.map = new google.maps.Map(document.getElementById('map'), { zoom: 12, center: loc, scrollwheel: false }); updateRestaurants(); }
