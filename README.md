# Product-Display-Card
This is a code for a product card that displays a product image, its name, and a button to take an action. The code uses HTML and CSS to create a visually appealing product card with a 3D effect. When the user hovers over the card, the card rotates, and the button changes its shape.

The card is contained within a container class that is positioned in the center of the page using the display flex property. The card is further divided into three parts: the effect, background, and the card.

The effect class contains a circular-shaped effect that appears when the user hovers over the card. It uses a transition property to animate its appearance.

The background class contains an image of the product that is displayed in the background of the card. The mix-blend-mode property is used to multiply the image with the background color.

The card class is the main part of the product card that displays the product name and image, as well as a button to take an action. The card uses the z-index property to position itself above the background and effect classes. The card also contains a pseudo-element to create a border around the card.

When the user hovers over the card, it rotates using the transform property, and the button changes its shape using the :before and :after pseudo-elements. The button also scales down using the transform property.

Overall, the code creates an impressive product card that can be used to showcase products on a website or online store.
