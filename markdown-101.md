# Markdown 101

#### Writing paragraphs
* To insert paragraphs, just separate texts with a full line space in between
        
    _Markdown_  
    
        Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla tincidunt diam nibh, eget euismod ante vehicula vitae. Praesent mauris leo, malesuada malesuada dolor nec, pretium scelerisque purus. Suspendisse id ligula vel dui elementum fermentum quis id justo. Aenean in luctus diam. Fusce diam quam, vestibulum id posuere ut, tincidunt sed eros. Ut a bibendum est. Praesent euismod tempus sapien vitae tempor. Nulla eget rhoncus neque. Maecenas sit amet tortor libero. Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nullam diam tortor, pretium vitae commodo non, consequat et enim. Vestibulum interdum lorem urna, id lobortis urna dapibus at. Phasellus feugiat porttitor fringilla. Fusce aliquet nec lacus ut imperdiet.
        
        Curabitur venenatis porta arcu, at rutrum dolor iaculis eu. Curabitur tincidunt rhoncus purus, eget vestibulum libero consequat a. Maecenas consequat auctor nisi, at auctor purus ultrices sit amet. Aliquam facilisis, ante congue vehicula semper, tellus quam aliquam mi, nec facilisis quam sem a augue. Sed volutpat, purus a vestibulum pellentesque, massa nisl auctor sapien, a mattis justo ante non diam. Ut scelerisque elementum luctus. Aliquam erat volutpat. Duis mattis ac erat non ultricies.
        
        Phasellus rutrum justo a nibh pretium, at dapibus augue malesuada. Aenean sed porttitor odio, sed mollis magna. Nulla venenatis accumsan turpis, eget finibus ipsum molestie ac. Vestibulum ornare quis lectus et consequat. Sed efficitur nec sapien vitae imperdiet. Integer id lobortis erat, a vestibulum urna. Mauris pulvinar eu ex vel ullamcorper. Vestibulum tincidunt ante consequat urna suscipit, vel sodales sem aliquet. Vestibulum condimentum tortor nunc, a volutpat dolor auctor vitae. Suspendisse potenti. Ut efficitur vel magna eget gravida. Cras vestibulum purus nec fermentum lobortis. Aliquam erat volutpat. Duis iaculis augue non libero maximus, quis lobortis nisi volutpat. Ut placerat mi et metus bibendum tristique.
        
    _Result_
    
    Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla tincidunt diam nibh, eget euismod ante vehicula vitae. Praesent mauris leo, malesuada malesuada dolor nec, pretium scelerisque purus. Suspendisse id ligula vel dui elementum fermentum quis id justo. Aenean in luctus diam. Fusce diam quam, vestibulum id posuere ut, tincidunt sed eros. Ut a bibendum est. Praesent euismod tempus sapien vitae tempor. Nulla eget rhoncus neque. Maecenas sit amet tortor libero. Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nullam diam tortor, pretium vitae commodo non, consequat et enim. Vestibulum interdum lorem urna, id lobortis urna dapibus at. Phasellus feugiat porttitor fringilla. Fusce aliquet nec lacus ut imperdiet.
            
    Curabitur venenatis porta arcu, at rutrum dolor iaculis eu. Curabitur tincidunt rhoncus purus, eget vestibulum libero consequat a. Maecenas consequat auctor nisi, at auctor purus ultrices sit amet. Aliquam facilisis, ante congue vehicula semper, tellus quam aliquam mi, nec facilisis quam sem a augue. Sed volutpat, purus a vestibulum pellentesque, massa nisl auctor sapien, a mattis justo ante non diam. Ut scelerisque elementum luctus. Aliquam erat volutpat. Duis mattis ac erat non ultricies.
            
    Phasellus rutrum justo a nibh pretium, at dapibus augue malesuada. Aenean sed porttitor odio, sed mollis magna. Nulla venenatis accumsan turpis, eget finibus ipsum molestie ac. Vestibulum ornare quis lectus et consequat. Sed efficitur nec sapien vitae imperdiet. Integer id lobortis erat, a vestibulum urna. Mauris pulvinar eu ex vel ullamcorper. Vestibulum tincidunt ante consequat urna suscipit, vel sodales sem aliquet. Vestibulum condimentum tortor nunc, a volutpat dolor auctor vitae. Suspendisse potenti. Ut efficitur vel magna eget gravida. Cras vestibulum purus nec fermentum lobortis. Aliquam erat volutpat. Duis iaculis augue non libero maximus, quis lobortis nisi volutpat. Ut placerat mi et metus bibendum tristique.

#### Bold and Italic
* To bold a text, just surround the word or phrase with two asterisks(*) or underscores(_)
        
    _Markdown_  
    
        What a **wonderful** day
        
        Welcome to **Markdown Syntax**
        
        We can also use a __double underscore__
        
    _Result_
    
    What a **wonderful** day  
    
    Welcome to **Markdown Syntax**
    
    We can also use a __double underscore__

* To italicize a text, just surround the word or phrase with one asterisk(*) or underscore(_)
        
    _Markdown_  
        
            What a *wonderful* day
            
            Welcome to *Markdown Syntax*
            
            We can also use a _double underscore_
            
    _Result_
    
    What a *wonderful* day
                
    Welcome to *Markdown Syntax*
    
    We can also use a _double underscore_
    
    
#### Strikethrough 
* To strikethrough a text, just surround the word or phrase with two tildes(~)
        
    _Markdown_  
    
        What a ~~wonderful~~ day
        
        Welcome to ~~Markdown Syntax~~
                
    _Result_
    
    What a ~~wonderful~~ day
            
    Welcome to ~~Markdown Syntax~~
    
    
#### Image 
* To insert an image, use `![ALTERNATIVE_TEXT](IMAGE_PATH "TEXT_TO_SHOW_ON_HOVER")`
        
    _Markdown_  
    
        ![Railroad](https://unsplash.it/500/500 "Railroad")
                
    _Result_
    
    ![Railroad](https://unsplash.it/500/500 "Railroad")
    
* To link an image with a variable:
        
    _Markdown_  
    
        ![Bay Shore][path]
        
        [path]: https://unsplash.it/400/400
                
    _Result_
    
    ![Bay Shore][path]
    
    [path]: https://unsplash.it/400/400
    
* To link text to an image:
        
    _Markdown_  
    
        [Show Image](https://unsplash.it/400/400)
                
    _Result_
   
    [Show Image](https://unsplash.it/400/400)
  
* To link an image to an bigger version of that image:
        
    _Markdown_  
    
        [![](https://unsplash.it/100/100?image=1000)](https://unsplash.it/500/500?image=1000)
                
    _Result_
   
    [![](https://unsplash.it/100/100?image=1000)](https://unsplash.it/500/500?image=1000)
              
