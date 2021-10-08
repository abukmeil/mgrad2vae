# Mgrad2vae
Explainable autonomous driving systems (EADS) are emerging recently as a combination of explainable artificial intelligence (XAI) and vehicular automation (VA). EADS explains events, ambient environments, and engine operations of an autonomous driving vehicular, and it also delivers explainable results in an orderly manner. Explainable semantic segmentation (ESS) plays an essential role in building EADS, where it offers visual attention that helps the drivers to be aware of the ambient objects irrespective if they are roads, pedestrians, animals, or other objects. In this paper, we propose the first ESS model for EADS based on the variational autoencoder (VAE), and it uses the multiscale second-order derivatives between the latent space and the encoder layers to capture the curvatures of the neurons’ responses. Our model is termed as Mgrad2VAE and is bench-marked on the SYNTHIA and A2D2 datasets, where it outperforms the recent models in terms of image segmentation metrics.




Python source code for the paper:

M. Abukmeil, A. Genovese, V. Piuri, F. Rundo, and F. Scotti, "Towards explainable semantic segmentation for autonomous driving systems by multi-scale variational attention", in Proc. of the 1st  IEEE Int. Conf. on Autonomous Systems (ICAS 2021), Montreal, Canada, August 11-13, 2021, pp. 1-5. ISBN: 978-1-7281-7289-7. 




Project page:

https://iebil.di.unimi.it/mgradvae/index.htm


# Outline:

![outline](https://user-images.githubusercontent.com/50661098/131345520-75f49468-c613-406c-8184-a53fba63e94f.jpg)









  Citation:
  
    @InProceedings {icas21_unimi,
			author = {M. Abukmeil and A. Genovese and V. Piuri and F. Rundo and F. Scotti},
			title = {Towards explainable semantic segmentation for autonomous driving systems by multi-scale variational attention},
			booktitle = {Proc. of the 1st IEEE Int. Conf. on Autonomous Systems (ICAS 2021)},
			address = {Montreal, Canada},
			pages = {1-5},
			month = {August},
			day = {11-13},
			year = {2021},
			note={978-1-7281-7289-7},}



Main files:

	• MgradVAE.ipynb: main file


The databases used in the paper can be obtained at:

SYNTHIA

https://synthia-dataset.net/

A2D2

https://www.a2d2.audi/a2d2/en.html


