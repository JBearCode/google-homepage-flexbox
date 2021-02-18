Hi, this is my first ever web project that I'm doing as part of The Odin Project curriculum. The goal is to replicate the look of the Google homepage.

In my initial attempt I managed to get everything working except for the three icons: the google apps icon in the top right menu, and the two icons in the search bar.

As I read up on how to get those positioned, I decided to start from scratch and build the project again using flexbox. In this second attempt, I also made more comments in the CSS to help me remember what everything was for and work more quickly.

I started with the structure of the top menu (a flexbox row), the main content (a flexbox column), and the footer menu (a flexbox row).

To make the footer stick to the bottom, I put all three main sections into another flexbox column and gave the main content a flex-grow value of 1.

I liked how easy it was to use margin-left: auto to shift some menu items to the right side. Using justify-content: space-between for the searchbar's two icons also worked really well (all within a flex div).

I finished by adding some CSS hover effects.

It's not much, but I'm excited to have finished my first project.


