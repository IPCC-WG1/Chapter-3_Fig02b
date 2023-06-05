##########################################################################
# ---------------------------------------------------------------------------------------------------------------------
# This is Python code to produce IPCC AR6 WGI Figure 3.2b 
# Creator: Chris Brierley, Anni Zhao  
# Contact: c.brierley@ucl.ac.uk, anni.zhao.16@ucl.ac.uk
# Last updated on: March 1st, 2021
# --------------------------------------------------------------------------------------------------------------------
#
# - Code functionality: Generates Figure 3.2 panel b in the IPCC Working Group I Contribution to the Sixth Assessment Report: Chapter 3
# - Input data: fig3.2b_1pctCO2_CMIP5.csv, fig3.2b_1pctCO2_CMIP5_ensemble_mean.csv, fig3.2b_1pctCO2_CMIP6.csv,fig3.2b_1pctCO2_CMIP6_ensemble_mean.csv
                fig3.2b_abrupt4xCO2_CMIP5.csv, fig3.2b_abrupt4xCO2_CMIP5_ensemble_mean.csv, fig3.2b_abrupt4xCO2_CMIP6.csv,
                fig3.2b_abrupt4xCO2_CMIP6_ensemble_mean.csv, fig3.2b_EECO_CMIP6.csv, fig3.2b_EECO_CMIP6_ensemble_mean.csv,
                fig3.2b_EECO_nonCMIP.csv, fig3.2b_EECO_nonCMIP_ensemble_mean.csv, fig3.2b_LGM_CMIP5.csv, fig3.2b_LGM_CMIP5_ensemble_mean.csv
                fig3.2b_LGM_CMIP6.csv, fig3.2b_LGM_CMIP6_ensemble_mean.csv, fig3.2b_LGM_nonCMIP.csv, fig3.2b_LGM_nonCMIP_ensemble_mean.csv,
                fig3.2b_LIG_CMIP6.csv, fig3.2b_LIG_CMIP6_ensemble_mean.csv, fig3.2b_LIG_nonCMIP.csv,  fig3.2b_LIG_nonCMIP_ensemble_mean.csv
                fig3.2b_MH_CMIP5.csv, fig3.2b_MH_CMIP5_ensemble_mean.csv, fig3.2b_MH_CMIP6.csv, fig3.2b_MH_CMIP6_ensemble_mean.csv,
		fig3.2b_MH_nonCMIP.csv, fig3.2b_MH_nonCMIP_ensemble_mean.csv, fig3.2b_mPWP_CMIP6.csv, fig3.2b_mPWP_CMIP6_ensemble_mean.csv,
           	fig3.2b_mPWP_nonCMIP.csv, fig3.2b_mPWP_nonCMIP_ensemble_mean.csv, fig3.2b_observation_instrumental.csv,
           	fig3.2b_observation_reconstruction.csv
#
#
#
#
#
# - Output variables: 
#
# ----------------------------------------------------------------------------------------------------
# Information on  the software used
# - Software Version: [insert version]*
# - Landing page to access the software: [if possible provide a DOI]* 
# - Operating System: [insert operating system and date of last update]*
# - Environment required to compile and run: [insert here]*
#  ----------------------------------------------------------------------------------------------------
#
#  License: Apache 2.0
# ----------------------------------------------------------------------------------------------------
# How to cite:
# When citing this code, please include both the code citation and the following citation for the related report component:
Figure 3.2 in IPCC, 2021: Chapter 3. In: Climate Change 2021: The Physical Science Basis. Contribution of Working Group I to 
the Sixth Assessment Report of the Intergovernmental Panel on Climate Change [Eyring, V., N.P. Gillett, K.M. Achuta Rao, R. Barimalala,
 M. Barreiro Parrillo, N. Bellouin, C. Cassou, P.J. Durack, Y. Kosaka, S. McGregor, S. Min, O. Morgenstern, and Y. Sun, 2021: Human 
Influence on the Climate System. In Climate Change 2021: The Physical Science Basis. 
Contribution of Working Group I to the Sixth Assessment Report of the Intergovernmental Panel on Climate Change [Masson-Delmotte, V., 
P. Zhai, A. Pirani, S.L. Connors, C. Péan, S. Berger, N. Caud, Y. Chen, L. Goldfarb, M.I. Gomis, M. Huang, K. Leitzell, E. Lonnoy, 
J.B.R. Matthews, T.K. Maycock, T. Waterfield, O. Yelekçi, R. Yu, and B. Zhou (eds.)]. 
Cambridge University Press, Cambridge, United Kingdom and New York, NY, USA, pp. 423–552, doi: 10.1017/9781009157896.005 .]