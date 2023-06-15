# CGE_demo
This code is the framework of the proposed framwork CGE.

To compare our framework with existing post-hoc explanation methods, please run python main.py.
For example, to compare GNNExplainer with CGE-GNNExplainer in the dataset MUTAG, please add 5 (GNNExplainer) and 11 (CGE-GNNExplainer) to the list of Explainers in explain_module\utils\parser.py, then run main.py.  Similarly， to compare Explainer h with CGE-h, please change the part of GNNExplainer to h in explain_module\attribution_model_zoo\meta_cge_gnn_2 , then run python main.py. 

Thanks！
