# Master Thesis: A large-scale brain network study on the effect of virtual so-tDCS on slow wave activity in young and old healthy adults.

## Simulation and Analysis
This repo stores Jupyter notebooks used in this project. There are 3 files in total.
1. **SimNIBS_efield.ipynb** In this notebook, we used SimNIBS (Thielscher et al., 2015) to simulate the electric field (E-field) when applying transcranial slow oscillatory stimulation (so-tDCS) on the virtual scalp.   
2. **TVB_simulation.ipynb** In this notebook, we simulated the effect of so-tDCS on the brain network model using TVB (Ritter et al., 2013; Sanz Leon et al., 2013; Schirner et al., 2022). We injected the E-fields from SimNIBS to the model.
3. **Analysis.ipynb** In this notebook, we analyzed simulated brain activity resulting from TVB.

## Reference
- Ritter, P., Schirner, M., McIntosh, A. R., & Jirsa, V. K. (2013). The Virtual Brain Integrates Computational Modeling and Multimodal Neuroimaging. Brain Connectivity, 3(2), 121–145. https://doi.org/10.1089/brain.2012.0120
- Sanz Leon, P., Knock, S. A., Woodman, M. M., Domide, L., Mersmann, J., McIntosh, A. R., & Jirsa, V. (2013). The Virtual Brain: A simulator of primate brain network dynamics. Frontiers in Neuroinformatics, 7. https://doi.org/10.3389/fninf.2013.00010
- Schirner, M., Domide, L., Perdikis, D., Triebkorn, P., Stefanovski, L., Pai, R., Prodan, P., Valean, B., Palmer, J., Langford, C., Blickensdörfer, A., Van Der Vlag, M., Diaz-Pier, S., Peyser, A., Klijn, W., Pleiter, D., Nahm, A., Schmid, O., Woodman, M., … Ritter, P. (2022). Brain simulation as a cloud service: The Virtual Brain on EBRAINS. NeuroImage, 251, 118973. https://doi.org/10.1016/j.neuroimage.2022.118973
- Thielscher, A., Antunes, A., & Saturnino, G. B. (2015). Field modeling for transcranial magnetic stimulation: A useful tool to understand the physiological effects of TMS? 2015 37th Annual International Conference of the IEEE Engineering in Medicine and Biology Society (EMBC), 222–225. https://doi.org/10.1109/EMBC.2015.7318340
