If you want to support me, you can cites some of my works here:
	https://gist.github.com/thieunguyen5991/2dcebc754bf0038d0c12b26ec9d591aa

I have done the original version of SMA like in paper. (OriginalSMA in file: SMA.py)
I also created new my modified of SMA - faster and better (BaseSMA in file: SMA.py)

The root.py file contain some useful helper functions which used in SMA.py file.
Run the test_SMA.py by:
	python test_SMA.py

You need libraries:
	python >= 3.7.6
	numpy >= 1.18.1

#!/usr/bin/env python
# ------------------------------------------------------------------------------------------------------%
# Python code created by "Thieu Nguyen" at 21:29, 12/06/2020                                                        %
#                                                                                                       %
#       Email:      nguyenthieu2102@gmail.com                                                           %
#       Homepage:   https://www.researchgate.net/profile/Thieu_Nguyen6                                  %
#       Github:     https://github.com/thieunguyen5991                                                  %
#-------------------------------------------------------------------------------------------------------%

# Main paper (Please refer to the main paper):
# Slime Mould Algorithm: A New Method for Stochastic Optimization
# Shimin Li, Huiling Chen, Mingjing Wang, Ali Asghar Heidari, Seyedali Mirjalili
# Future Generation Computer Systems,2020
# DOI: https://doi.org/10.1016/j.future.2020.03.055
# https://www.sciencedirect.com/science/article/pii/S0167739X19320941
# ------------------------------------------------------------------------------------------------------------
# Website of SMA: http://www.alimirjalili.com/SMA.html
# You can find and run the SMA code online at http://www.alimirjalili.com/SMA.html

# You can find the SMA paper at https://doi.org/10.1016/j.future.2020.03.055
# Please follow the paper for related updates in researchgate: 
# https://www.researchgate.net/publication/340431861_Slime_mould_algorithm_A_new_method_for_stochastic_optimization
# ------------------------------------------------------------------------------------------------------------
#  Main idea: Shimin Li
#  Author and programmer: Shimin Li,Ali Asghar Heidari,Huiling Chen
#  e-Mail: simonlishimin@foxmail.com
# ------------------------------------------------------------------------------------------------------------
#  Co-author:
#             Huiling Chen(chenhuiling.jlu@gmail.com)
#             Mingjing Wang(wangmingjing.style@gmail.com)
#             Ali Asghar Heidari(aliasghar68@gmail.com, as_heidari@ut.ac.ir)
#             Seyedali Mirjalili(ali.mirjalili@gmail.com)
#             
#             Researchgate: Ali Asghar Heidari https://www.researchgate.net/profile/Ali_Asghar_Heidari
#             Researchgate: Seyedali Mirjalili https://www.researchgate.net/profile/Seyedali_Mirjalili
#             Researchgate: Huiling Chen https://www.researchgate.net/profile/Huiling_Chen
# ------------------------------------------------------------------------------------------------------------
