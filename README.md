l1_and_l2_loss_function
=======================

Visualizing the differences between L1-norm and L2-norm loss function

Script to validate visually the stability property of L1-norm and L2-norm loss function.

Experiment Design:
- Generate N basic points at with varying y = b * x + c + random_number.
- Generate M datasets with an outlier point clearly outside this range.
- Plot M graphs to see how different outlier points will cause the different model to behave.
