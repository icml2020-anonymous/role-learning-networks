# Role Learning Networks

This is the code accompanying the ICML 2020 submission Discovering the Compositional Structure of Vector Representations with Role Learning Networks.

# The ROLE Model
For the complete architecture, see [RoleLearningTensorProductEncoder](https://github.com/icml2020-anonymous/role-learning-networks/blob/master/rolelearner/role_learning_tensor_product_encoder.py).
If you are interested in the role learning module depicted in Figure 1, see [RoleAssignmentLSTM](https://github.com/icml2020-anonymous/role-learning-networks/blob/master/rolelearner/role_assigner.py).

# Using ROLE

To train a ROLE model, you want to use ```decompose.py```. You need to place your training files
in the data/ directory (see the example files there). Then you run:

```
python decompose.py --data_prefix example --num_roles NUM_ROLES --filler_dim FILLER_DIM --role_dim ROLE_DIM --role_learning
```
