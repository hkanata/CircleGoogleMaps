# CircleGoogleMaps

http://opba.com.br

hkanata@gmail.com

Example: http://opba.com.br/circle
Example: https://opba.com.br/circle

This is a fixed version of google maps circle.

Below follow what was fixed.

OLD: noteB.text(bounds.contains(latLngB));

NEW: noteA.text(google.maps.geometry.spherical.computeDistanceBetween(circle.getCenter(), latLngA) <= circle.getRadius());

