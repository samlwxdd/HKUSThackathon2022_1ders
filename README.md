# HackUST2022_1ders

Credits:

1. jQuery Library (Under MIT License) (By JS Foundation): http://jquery.org/license/
2. MaterializeCSS (Under MIT License) (By Materialize): https://raw.githubusercontent.com/Dogfalo/materialize/master/LICENSE
3. tensorflow.js (Apache License 2.0): https://github.com/tensorflow/tfjs/blob/master/LICENSE
4. Google Fonts (Roboto) (Apache License 2.0) (By Christian Robertson): https://fonts.google.com/specimen/Roboto#license
5. plus/minus input counter (By rkoms): https://codepen.io/rkoms/pen/OJbrGKX
6. Easy Web3 Meta Mask Login (By Timothy Carambat): https://gist.github.com/timothycarambat/e7e014a6fd08f33e753bcf2f9e31239e 

Explanation of Submission:

This is a prototype of Good1.com, a shopping platform that integrates Blockchain, NFT and Machine Learning.
As it is only a static website aiming to simulate the real shopping experience as a customer/merchant, no databases are required to run the webpage.
In the future, the website has a possibility to integrate with server-side scripting (e.g. PHP+MySQL).

Please follow the steps below to try on the website

1. (index.html) Initialy, you are a visitor, click login on the top-right-hand corner to sign in.
2. (login.html) You can choose to sign in using a Metamask crypto wallet, or click the login button directly.

3. (login_index.html) Click the search button / save button under the filters to apply search criteria.
4. (search.html) Yellow Blouse will be filtered out. You can click on the three dots to see the short description, or click on the image to the item page.
5. (item.html) At this page, the details of the yellow blouse will be shown (including the link to the NFT version of the clothes in OpenSea).
Similar items/Items you've visited/Recommendation will be shown in the page too.
Select Size "S" and quantity 1, click "Add to Cart"
6. (item.html#window) A reminder for repeated purchase will pop up. Click "Proceed to Checkout" to continue.
7. (cart.html) Preview your shopping cart.
You can click the start button, and try on the Instant Check function, by showing the Yellow Blouse image to the camera.
It will tell you that it's 100% similar to an item in the cart, so that you can consider removing it.

8. (buyers.html) Click "Backend (As a Buyer)" on the navigation bar.
If you logged in with Metamask, your blockchain address will be shown.
You can take a look on the electronic wardrobe and browsing history.

9. (sellers.html) Click "Upload Items (As a Seller)" on the navigation bar.
Your role is the shop owner of Shop ABC. All of the details of the new product "T-Shirt" is prefilled.
Click "Save As Draft"->"Pubish it instead" or "Submit". You will be guided to the preview page.
10. (preview.html) You can take a look on how the website will be after the item is published.
Click "Publish" on the left-hand side to pubish the item.

11. The trial is ended here. Click "Logout" on the navigation bar to return to index.html.

5 more machine learning models are attached here for you to try on.
1. Tops, Bottoms, Underwear (Pants / Clothes / Underwear): https://teachablemachine.withgoogle.com/models/dt4CQbjiI/ 
2. Tops Types (Cardigan / Jacket / Shirts): https://teachablemachine.withgoogle.com/models/R47ShBzBA/
3. Underwear Types (Boxer / Vest / Y-front): https://teachablemachine.withgoogle.com/models/EbBJPC9Xz/
4. Bottoms Types (Pants / Shorts / Skirt): https://teachablemachine.withgoogle.com/models/4Wwdt6IrS/ 
5. Branding (Adidas / Nike / New Balance): https://teachablemachine.withgoogle.com/models/rKEoCcrmp/
