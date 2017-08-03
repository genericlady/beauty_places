# Beauty Places
This is a REACT and Rails project that leverages geocoding and
google places API to search for Beauty Places that are of the 
hair, skin and nails type.

# [REACT with Redux Client](https://github.com/genericlady/beauty_places_client)
This makes use of Redux to return state based off of actions that are
dispatching messages with payloads. This is so we can have an immutable
state while still being able to share it amongst a container and it's 
components.

# [Ruby API](https://github.com/genericlady/beauty_places_api)
This API is very minimal. Firstly we installed it with minimal middleware
since we don't need support for things like ERB since this is just a backend
that serves up json. It's main two responsibilities is Geocoding and 
looking up places of beauty against the Google Places API.

