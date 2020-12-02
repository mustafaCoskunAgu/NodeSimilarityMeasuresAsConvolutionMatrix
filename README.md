# NodeSimilarityMeasuresAsConvolutionMatrix

This github page created as a source code for the paper, https://github.com/mustafaCoskunAgu/NodeSimilarityMeasuresAsConvolutionMatrix/blob/main/Node_Similarity_Based_Graph_Convolution_for_Link_Prediction_in_Biological_Networks.pdf, that is submitted  to Bioinformatics Journal.

Requirements

Python 3.6

pytorch

networkx

pandas

scipy

scikit-learn

numpy

...

Run 

main.py


Change
    parser.add_argument('--embTech', choices=[
        'DGI',
        'CN',
        'AA',
        
    ], default='HDI', help='The embedding learning method')
For various convolution matrix option change HDI to RA, HPI,etc.


For any question email me via mustafa.coskun@agu.edu.tr

Cite

@article {Co{\c s}kun2020.11.14.382655,
	author = {Co{\c s}kun, Mustafa and Koyut{\"u}rk, Mehmet},
	title = {Proximity Measures as Graph Convolution Matrices for Link Prediction in Biological Networks},
	elocation-id = {2020.11.14.382655},
	year = {2020},
	doi = {10.1101/2020.11.14.382655},
	publisher = {Cold Spring Harbor Laboratory},
	abstract = {Motivation Link prediction is an important and well-studied problem in computational biology, with a broad range of applications including disease gene prioritization, drug-disease associations, and drug response in cancer. The general principle in link prediction is to use the topological characteristics and the attributes{\textendash}if available{\textendash} of the nodes in the network to predict new links that are likely to emerge/disappear. Recently, graph representation learning methods, which aim to learn a low-dimensional representation of topological characteristics and the attributes of the nodes, have drawn increasing attention to solve the link prediction problem via learnt low-dimensional features. Most prominently, Graph Convolution Network (GCN)-based network embedding methods have demonstrated great promise in link prediction due to their ability of capturing non-linear information of the network. To date, GCN-based network embedding algorithms utilize a Laplacian matrix in their convolution layers as the convolution matrix and the effect of the convolution matrix on algorithm performance has not been comprehensively characterized in the context of link prediction in biomedical networks. On the other hand, for a variety of biomedical link prediction tasks, traditional node similarity measures such as Common Neighbor, Ademic-Adar, and other have shown promising results, and hence there is a need to systematically evaluate the node similarity measures as convolution matrices in terms of their usability and potential to further the state-of-the-art.Results We select 8 representative node similarity measures as convolution matrices within the single-layered GCN graph embedding method and conduct a systematic comparison on 3 important biomedical link prediction tasks: drug-disease association (DDA) prediction, drug{\textendash}drug interaction (DDI) prediction, protein{\textendash}protein interaction (PPI) prediction. Our experimental results demonstrate that the node similarity-based convolution matrices significantly improves GCN-based embedding algorithms and deserve more attention in the future biomedical link predictionAvailability Our method is implemented as a python library and is available at githublinkContact mustafa.coskun{at}agu.edu.trSupplementary information Supplementary data are available at Bioinformatics online.Competing Interest StatementThe authors have declared no competing interest.},
	URL = {https://www.biorxiv.org/content/early/2020/11/16/2020.11.14.382655},
	eprint = {https://www.biorxiv.org/content/early/2020/11/16/2020.11.14.382655.full.pdf},
	journal = {bioRxiv}
}
