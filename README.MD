# Approaches to Secure Image Rendering on the Web



basically a jpeg DRM engine

- Disregard the <img> tag

- Buffer + HashMap approach
 - flatten the image into a buffer of pixels
 - use hashmap that has image dimensions, slices, instructions.......
 - offers individual manipulation of pixels for pricise, creative effects 

 - Secure Client
  - create a secure webclient with soft authentication (for views/tracking)

  - keep client as is, I don't feel like rewriting the fron-tend in react. It would be a good excercise, but no


 forked off (https://github.com/meixler/web-browser-based-file-encryption-decryption)