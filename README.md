SOURCES:
----
Begginer's guide
1. [Part1 - How to use SD](https://stable-diffusion-art.com/beginners-guide/)
2. [Part2 - Prompts](https://stable-diffusion-art.com/how-to-come-up-with-good-prompts-for-ai-image-generation/)
3. [Part3 - Inpainting](https://stable-diffusion-art.com/inpainting_basics/)
4. [Part4 - Models](https://stable-diffusion-art.com/models/)

5. [Install SD with API](https://www.reddit.com/r/StableDiffusion/comments/y20aym/local_installation_of_stable_diffusion_with_a/?rdt=45718)
6. [API documentation](https://github.com/AUTOMATIC1111/stable-diffusion-webui/wiki/API)
7. 





Info to keep in mind:
---
1. Can be done in the cloud with AUTOMATIC1111: [setup guide](https://andrewongai.gumroad.com/l/stable_diffusion_quick_start) 
2. there is a [prompt generator](https://andrewongai.gumroad.com/l/stable_diffusion_prompt_generator)
3. Inpainting tips at the end of the source page should solve 90% of the problems
4. We can introduce anyone in a custom model with only 5 images and special keyword using Dreambooth. 


Dreambooth, initially developed by Google, is a technique to inject custom subjects into text-to-image models. It works with as few as 3-5 custom images. You can take a few pictures of yourself and use Dreambooth to put yourself into the model. A model trained with Dreambooth requires a special keyword to condition the model.

There’s another less popular fine-tuning technique called textual inversion (sometimes called embedding). The goal is similar to Dreambooth: Inject a custom subject into the model with only a few examples. A new keyword is created specifically for the new object. Only the text embedding network is fine-tuned while keeping the rest of the model unchanged. In layman’s terms, it’s like using existing words to describe a new concept.

 
 1-click Google Colab notebook running AUTOMATIC1111 GUI
 ----
 I need a paid Google Colab Pro account ~ $10/month
 
 extensions:
 ----
 
[DREAMBOOTH: generate consistent face with Stable Diffusion](https://stable-diffusion-art.com/dreambooth/)
get same face on several pictures for storyboards ....
[CONTROLNET: Background, position of characters...  youyutbe tuto](https://m.youtube.com/watch?v=YephV6ptxeQ&feature=youtu.be)

API NEWS
----
[documentation](https://stablediffusionapi.com/docs/)
[youtube tuto](https://www.youtube.com/@stablediffusionapi/videos)


LOCAL INSTALL
---
[local install on ubuntu](https://code.mendhak.com/run-stable-diffusion-on-ubuntu/)  
[harware and software requirements](https://invoke-ai.github.io/InvokeAI/installation/INSTALLATION/#docker-installation)

GRAPHIC CARD (geforce rtx 4060 ti by NVIDIA 8GB minimum)
---
looking at [amazon results](https://www.amazon.es/s?k=geforce+rtx+4060+ti&rh=n%3A937935031%2Cp_n_feature_browse-bin%3A28135916031&s=price-asc-rank&dc&ds=v1%3A4A96rl0Yi6OnlrjzxX8o4ULSGqdpvlBKAbq1%2BM5jNqU&__mk_es_ES=%C3%85M%C3%85%C5%BD%C3%95%C3%91&rnid=28135903031&ref=sr_nr_p_n_feature_browse-bin_2)
we can see that there are several techniucal point to consider such as:
1. RAM size (8GB min)
2. RAM type
3. Graphic card
4. Memory speed
5. Physical size card (enter in my PC?)

Possible candidates
----
334.9 euros(20231021): [Gigabyte NVIDIA GeForce RTX 3060](https://www.amazon.es/Gigabyte-GeForce-NVIDIA-VALIDO-MINERIA/dp/B096YK45Q2/ref=sr_1_10?__mk_es_ES=%C3%85M%C3%85%C5%BD%C3%95%C3%91&keywords=GeForce+RTX+4070&refinements=p_n_feature_browse-bin%3A28135916031%2Cp_36%3A30000-&rnid=1323854031&s=computers&sr=1-10)


AI to find AI
---
[site](https://theresanaiforthat.com/s/analyze+github+repository/)

PROJECT:
-----

There are several steps in this project, here tey qre from the simplest to the more complex one:

## Step 1:

Using SD, I want to generate a storyboard representing actual life situation. I want to use actual photos of persons and photos of locations to obtain a realistic result.
In order to do so I need the following:

1. be able to generate the same persons anytime I want in various positions and actions (walking, sleeping, playing....)
  1. the same prompt must generate the same result each time, specially about the person faces and shapes
2. be able to add in the background the various scenes I need such as livi
ng room, kitchen, parc ....
3. be able to generate a comic form with chosen previous generated images, speaking bubbles, separation between generated images.....

 
### 20231021
We can install the API in local with sources number 5 and check the API doc with source number 6

Question: Can we use all the extension in this local API, I m thinking about inpainting, controlnet....

How to start the project:
----
1. Get the appropriate GPU
2. Install the local webUI
3. Try without local API first:
   1. train my model for myself, Paula and Gabrielle (and Papou madou) with [Dreambooth](https://stable-diffusion-art.com/dreambooth/)   
   2. use already existing prompts available in [civitAI](https://civitai.com/images/2413821?modelVersionId=157834&prioritizedUserIds=1819123&period=AllTime&sort=Most+Reactions&limit=20)
   3. use [controlNet](https://m.youtube.com/watch?v=YephV6ptxeQ&feature=youtu.be) to get background, positions... 
4. Try same work with local API?
5. [Video of guy who made comic with SD](https://www.youtube.com/watch?v=tmGL-QTahwA)
   1. 
6. 



