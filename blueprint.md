FORMAT: 1A

# Android Content API
This API contain services for retrieving pages and containers and optimize it for Android devices 


## /android/1.1/content/page/{pageid}


+ Parameters

    + pageid (string, `home`) ... An unique identifier (as defined in AppGrid) of the page
    
### GET 
    
+ Response 200 (application/json)

    + Headers


    + Body

            { "abc": "defxy" }

##/android/1.1/content/page/{pageid}/container/{containerid}

+ Parameters

    + pageid (string, `home`) ... An unique identifier (as defined in AppGrid) of the page
    + containerid (string, `top`) ... An unique identifier (as defined in AppGrid) of the container

## GET 

+ Response 200 (application/json)

    + Headers


    + Body

            { "abc": "def" }
