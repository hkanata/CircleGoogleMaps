# CircleGoogleMaps

This is a fixed version of google maps circle. \n

Below follow what was fixed. \n

# OLD: noteB.text(bounds.contains(latLngB));
# NEW: noteA.text(google.maps.geometry.spherical.computeDistanceBetween(circle.getCenter(), latLngA) <= circle.getRadius());

