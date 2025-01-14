| [HOME](README.md) |   [Videos](VIDEOS.md)       |
| -------- | ------------------------------------ |

# Tutorials_Libra
Tutorials showcasing various capabilities of Libra

## TOC

1. Rigid body
 * 1.1. [Construct & describe properties of rigid bodies](1_rigid_body/1_setup)

2. Integrators
 * 2.1. [Runge-Kutta 4-th order for Classical Mechanics](2_integrators/1_runge_kutta_4th_order)
 * 2.2. [Runge-Kutta 4-th order for Quantum Mechanics](2_integrators/2_runge_kutta_4_for_Liouville)

3. Linear algebra
 * 3.1. [operations with VECTOR, MATRIX, and CMATRIX data types](3_linear_algebra/1_vector_matrix_cmatrix_basics)
 * 3.2. [matrix functions, inversion, linear equations](3_linear_algebra/2_matrix_functions)

4. Optimization
 * 4.1. [Gradient descent optimizer](4_optimization/1_gradient_descent)
 * 4.2. [line search using DIIS](4_optimization/2_diis)

5. Electronic structure calculations in Libra
 * 5.1. [Extended Huckel Theory, EHT](5_electronic_structure/1_eht)
    * 5.1.1. [Compact version](5_electronic_structure/1_eht/1_compact)
    * 5.1.2. [Detailed version](5_electronic_structure/1_eht/2_detailed)

 * 5.2. [Incomplete Neglect of Differential Overlap, INDO](5_electronic_structure/2_indo)
    * 5.2.1. [Compact version](5_electronic_structure/2_indo/1_compact)

6. Dynamics with Libra
 * 6.1. [Quantum-classical, trajectory methods](6_dynamics/1_trajectory_based)
   * 6.1.1. [Model, adiabatic MD](6_dynamics/1_trajectory_based/1_model_adiabatic)
        * 6.1.1.1. [NVE ensemble](6_dynamics/1_trajectory_based/1_model_adiabatic/1_nve)
        * 6.1.1.2. [NVT ensemble](6_dynamics/1_trajectory_based/1_model_adiabatic/2_nvt)
             * 6.1.1.2.1. [1 electronic state](6_dynamics/1_trajectory_based/1_model_adiabatic/2_nvt/1_1_state)
    * 6.1.2. [Model, common approach to adiabatic, Ehrenfest, and TSH](6_dynamics/1_trajectory_based/2_model_adiabatic)
    * 6.1.3. [Model, Ehrenfest recipes](6_dynamics/1_trajectory_based/3_model_ehrenfest_recipes)
    * 6.1.5. [Atomistic, adiabatic dynamics, ground/excited](6_dynamics/1_trajectory_based/5_atomistic_adiabatic_excited_states)
    * 6.1.6. [Model, NBRA and non-NBRA](6_dynamics/1_trajectory_based/6_model_nbra)
    * 6.1.7. [Model, TSH with thermostat, quantum-vs-classical partitioning of DOFs, and constrining](6_dynamics/1_trajectory_based/7_model_nonadiabatic_system_bath)

 * 6.2. [Quantum-classical, neglect-of-back-reaction trajectory workflows](6_dynamics/2_nbra_workflows)
    * 6.2.1. [step 1 with DFTB+](6_dynamics/2_nbra_workflows/1_step1_dftb)
    * 6.2.2. [step 1 with QE](6_dynamics/2_nbra_workflows/2_step1_qe)
    * 6.2.3. [step 2 with QE](6_dynamics/2_nbra_workflows/3_step2_qe)
    * 6.2.4. [step 3](6_dynamics/2_nbra_workflows/4_step3)
      * 6.2.4.1. [Compute single-particle NACs](6_dynamics/2_nbra_workflows/4_step3/1_build_SD_basis)
      * 6.2.4.2. [Compute many-body NACs](6_dynamics/2_nbra_workflows/4_step3/2_build_MB_basis)
    * 6.2.5. [step 4](6_dynamics/2_nbra_workflows/5_step4)
      * 6.2.5.1. [Initialze_data](6_dynamics/2_nbra_workflows/5_step4/1_initialize_data)
      * 6.2.5.2. [Dynamics](6_dynamics/2_nbra_workflows/5_step4/2_dynamics)
    * 6.2.6. [step 1 with CP2K](6_dynamics/2_nbra_workflows/6_step1_cp2k)
      * 6.2.6.1. [Molecular dynamics with DFT](6_dynamics/2_nbra_workflows/6_step1_cp2k/1_DFT)
      * 6.2.6.2. [Molecular dynamics with extended tight-binding](6_dynamics/2_nbra_workflows/6_step1_cp2k/2_xTB)
    * 6.2.7. [step 2 with CP2K](6_dynamics/2_nbra_workflows/7_step2_cp2k)
      * 6.2.7.1. [Compute molecular orbital overlaps and time-overlaps in DFT](6_dynamics/2_nbra_workflows/7_step2_cp2k/1_DFT)
      * 6.2.7.2. [Compute molecular orbital overlaps and time-overlaps in extended tight-binding](6_dynamics/2_nbra_workflows/7_step2_cp2k/2_xTB)
    * 6.2.8. [step 3 with CP2K](6_dynamics/2_nbra_workflows/8_step3_cp2k)
      * 6.2.8.1. [Computing nonadiabatic couplings in single-particle and many-body bases in DFT](6_dynamics/2_nbra_workflows/8_step3_cp2k/1_DFT)
      * 6.2.8.2. [Computing nonadiabatic couplings in single-particle basis in extended tight-binding](6_dynamics/2_nbra_workflows/8_step3_cp2k/2_xTB)
    * 6.2.9. [step 4 with sparse data files](6_dynamics/2_nbra_workflows/9_step4_cp2k)

 * 6.3. [Hierarchical equations of motion, HEOM](6_dynamics/3_heom)
    * 6.3.1. [Computing population dynamics and lineshapes](6_dynamics/3_heom/1_dynamics_and_lineshapes)

 * 6.4. [DVR, on-the-grid wavepackets](6_dynamics/4_wavepackets)
    * 6.4.1. [Gaussian wavepackets](6_dynamics/4_wavepackets/1_gaussian)
      * 6.4.1.1. [Computing matrix elements](6_dynamics/4_wavepackets/1_gaussian/1_matrix_elements)
    * 6.4.2. [DVR basics](6_dynamics/4_wavepackets/2_dvr_basics) 
    * 6.4.3. [SOFT dynamics in 1D and 2D](6_dynamics/4_wavepackets/3_soft_propagation)
    * 6.4.4. [More examples of DVR and dynamics](6_dynamics/4_wavepackets/4_more)

 * 6.5. [Fermi Golden Rule rates, FGR](6_dynamics/5_fgr)

7. Special functions
 * 7.1. [Sorting, matrix statistics](7_special_functions/1_sorting_matrix_statistics)
 * 7.2. [Fitting distributions to a superposition of Gaussians](7_special_functions/2_gaussian_kernel_algorithm)
 * 7.3. [Data statistics](7_special_functions/3_data_statistics)
 * 7.4. [Random numbers](7_special_functions/4_random_numbers)
    * 7.4.1. [Basic random number generator, chaotic systems](7_special_functions/4_random_numbers/1_basics)
    * 7.4.2. [Random number generation using Metropolis Monte Carlo method](7_special_functions/4_random_numbers/2_metropolis)

8. Model Hamiltonians
 * 8.1. [Define model Hamiltonians and plot PES](8_model_hamiltonians/1_pes_plotting)
 * 8.2. [Define atomistic Hamiltonians and plot PES](8_model_hamiltonians/2_interfaces_with_qchem_codes)

9. Machine learning
 * 9.1. [Basics of the artificial neural networks (ANNs), Multilayer Perceptron (MLP)](9_machine_learning/1_basics_of_mlp)
 * 9.2. [Analytical derivatives of the ANNs](9_machine_learning/2_ann_derivatives)
 * 9.3. [Advanced ANN training algorithms](9_machine_learning/3_advanced_ann)

10. Auxiliary functions and data types
 * 10.1. [Util functions and vectorized Libra types](10_auxiliary_functions/1_util_functions)

11. Program-specific methods
 * 11.1. [ErgoSCF methods](11_program_specific_methods/1_ergoscf_methods)
   * 11.1.1. [Basic methods](11_program_specific_methods/1_ergoscf_methods/1_basics)
   * 11.1.2. [Basic methods](11_program_specific_methods/1_ergoscf_methods/2_nac_workflow)
 * 11.2. [QE methods](11_program_specific_methods/2_qe_methods)
   * 11.2.1. [pDOS](11_program_specific_methods/2_qe_methods/1_pdos)
   * 11.2.2. [MD](11_program_specific_methods/2_qe_methods/2_md)
   * 11.2.3. [Normal modes](11_program_specific_methods/2_qe_methods/3_normal_modes)

12. Molecular builders
 * 12.1. [Crystal and QD builders](12_molecular_builders/1_crystal_and_qd_builder)
 * 12.2. [Chemobjects](12_molecular_builders/2_chemobjects)
   * 12.2.1. [Basic methods](12_molecular_builders/2_chemobjects/1_basic_construction_and_manipulaiton)
   * 12.2.2. [Rotations & Translations](12_molecular_builders/2_chemobjects/2_extended_rotation_and_translation)

13. Force fields and classical MD (outside the dynamics module)
  * 13.1. [Force field basics](13_force_fields_and_classical_md/1_force_field_basics)
  * 13.2. [Basics of MM calculations with Libra](13_force_fields_and_classical_md/2_atomistic_Hamiltonian)
  * 13.3. [Force field molecular structure optimization](13_force_fields_and_classical_md/3_mm_optimization)
  * 13.4. [Force field molecular dynamics](13_force_fields_and_classical_md/4_mm_md)  NEEDS MORE WORK

_______________________________

## Use cases

1. Create a chemical system
  * [5.1.1.](5_electronic_structure/1_eht/1_compact/tutorial.ipynb) |
  * [12.1.](12_molecular_builders/1_crystal_and_qd_builder/tutorial.ipynb)
  * [12.2.1.](12_molecular_builders/2_chemobjects/1_basic_construction_and_manipulaiton/tutorial.ipynb)
  * [13.3.](13_force_fields_and_classical_md/3_mm_optimization/tutorial.ipynb)
  
2. EHT calculations with Libra
  * [5.1.1.](5_electronic_structure/1_eht/1_compact/tutorial.ipynb)

3. INDO calculations with Libra
  * [5.2.1.](5_electronic_structure/2_indo/1_compact/tutorial.ipynb)

4. Compute .cube files from orbitals computed with Libra
  * [5.1.1.](5_electronic_structure/1_eht/1_compact/tutorial.ipynb)
  * [5.2.1.](5_electronic_structure/2_indo/1_compact/tutorial.ipynb)

5. Visualize the MOs from .cube files
  * [5.1.1.](5_electronic_structure/1_eht/1_compact/tutorial.ipynb)
  * [5.2.1.](5_electronic_structure/2_eht/1_compact/tutorial.ipynb)

6. Compute pDOS
  * [5.1.1.](5_electronic_structure/1_eht/1_compact/tutorial.ipynb)
  * [11.2.1.](11_program_specific_methods/2_qe_methods/1_pdos/tutorial.ipynb)

7. Plot pDOS
  * [5.1.1.](5_electronic_structure/1_eht/1_compact/tutorial.ipynb)
  * [11.2.1.](11_program_specific_methods/2_qe_methods/1_pdos/tutorial.ipynb)

8. Visualize MD trajectory with py3Dmol:
  * [6.1.5.](6_dynamics/1_trajectory_based/5_atomistic_adiabatic_excited_states/tutorial.ipynb)
  * [6.2.1.](6_dynamics/2_nbra_workflows/1_step1_dftb/tutorial.ipynb)
  * [8.2.](8_model_hamiltonians/2_interfaces_with_qchem_codes/tutorial.ipynb)
  * [11.2.2.](11_program_specific_methods/2_qe_methods/2_md/1_co2/tutorial.ipynb)
  * [12.2.1.](12_molecular_builders/2_chemobjects/1_basic_construction_and_manipulaiton/tutorial.ipynb)
  * [13.3.](13_force_fields_and_classical_md/3_mm_optimization/tutorial.ipynb)

9. Construct the vibronic Hamiltonian from the QE MD calculations
  * [6.2.3.](6_dynamics/2_nbra_workflows/3_step2_qe/tutorial.ipynb)

10. Read the vibronic Hamiltonian data files to obtain its properties
  * [6.2.3.](6_dynamics/2_nbra_workflows/3_step2_qe/tutorial.ipynb)
  * [6.2.4.1.](6_dynamics/2_nbra_workflows/4_step3/1_build_SD_basis/tutorial.ipynb)
  * [6.1.6.](6_dynamics/1_trajectory_based/6_model_nbra/tutorial.ipynb)
  * [6.1.7.](6_dynamics/1_trajectory_based/7_model_nonadiabatic_system_bath/tutorial.ipynb)

11. Compute the time-averaged nonadiabatic couplings of the vibronic Hamiltonian
  * [6.2.3.](6_dynamics/2_nbra_workflows/3_step2_qe/tutorial.ipynb)
  * [6.2.4.1.](6_dynamics/2_nbra_workflows/4_step3/1_build_SD_basis/tutorial.ipynb)
  * [6.2.4.2.](6_dynamics/2_nbra_workflows/4_step3/2_build_MB_basis/tutorial.ipynb)

12. Manually construct a Slater Determinant basis
  * [6.2.4.1.](6_dynamics/2_nbra_workflows/4_step3/1_build_SD_basis/tutorial.ipynb)

13. Auto-generate a Slater Determinant basis
  * [6.2.4.1.](6_dynamics/2_nbra_workflows/4_step3/1_build_SD_basis/tutorial.ipynb)

14. Compute the energies and nonadiabatic couplings in the SD basis
  * [6.2.4.1.](6_dynamics/2_nbra_workflows/4_step3/1_build_SD_basis/tutorial.ipynb)
  * [6.2.4.1.](6_dynamics/2_nbra_workflows/4_step3/2_build_MB_basis/tutorial.ipynb)

15. Calculate population and coherence dynamics of a quantum system embedded in a bath
  * [6.3.1.](6_dynamics/1_dynamics_and_lineshapes/3_heom/tutorial.ipynb)
   
16. Calculate absorbance spectral lineshapes of a quantum system embedded in a bath
  * [6.3.1.](6_dynamics/3_heom/1_dynamics_and_lineshapes/tutorial.ipynb)

17. Construct and plot the Heller's wavepackets
  * [6.4.1.1.](6_dynamics/4_wavepackets/1_gaussian/1_matrix_elements/tutorial.ipynb)

18. Compute the matrix elements of various operators with Heller's wavepackets
  * [6.4.1.1.](6_dynamics/4_wavepackets/1_gaussian/1_matrix_elements/tutorial.ipynb)

19. Define diabatic abstract model Hamiltonian 
  * [8.1.](8_model_hamiltonians/1_pes_plotting/tutorial.ipynb)
  * [6.1.7.](6_dynamics/1_trajectory_based/7_model_nonadiabatic_system_bath/tutorial.ipynb)

20. Define adiabatic abstract model Hamiltonian
  * [8.1.](8_model_hamiltonians/1_pes_plotting/tutorial.ipynb)

21. Define adiabatic file-based model Hamiltonian
  * [8.1.](8_model_hamiltonians/1_pes_plotting/tutorial.ipynb)
  * [6.1.6.](6_dynamics/1_trajectory_based/6_model_nbra/tutorial.ipynb)

22. Plot 1D PES 
  * [8.1.](8_model_hamiltonians/1_pes_plotting/tutorial.ipynb)
  * [8.2.](8_model_hamiltonians/2_interfaces_with_qchem_codes/tutorial.ipynb)
  * [6.1.6.](6_dynamics/1_trajectory_based/6_model_nbra/tutorial.ipynb)
  * [6.1.7.](6_dynamics/1_trajectory_based/7_model_nonadiabatic_system_bath/tutorial.ipynb)

23. Plot diabatic-to-adiabatic transformaitons vs. coordinate in 1D
  * [8.1.](8_model_hamiltonians/1_pes_plotting/tutorial.ipynb)

24. Plot 1D PES vs. time
  * [8.1.](8_model_hamiltonians/1_pes_plotting/tutorial.ipynb)
  * [6.1.6.](6_dynamics/1_trajectory_based/6_model_nbra/tutorial.ipynb)
  * [6.1.7.](6_dynamics/1_trajectory_based/7_model_nonadiabatic_system_bath/tutorial.ipynb)

25. Define Libra/Psi4 intraface Hamiltonian 
  * [8.2.](8_model_hamiltonians/2_interfaces_with_qchem_codes/tutorial.ipynb)

26. Define Libra/DFTB+ intraface Hamiltonian
  * [8.2.](8_model_hamiltonians/2_interfaces_with_qchem_codes/tutorial.ipynb)
  * [6.1.5.](6_dynamics/1_trajectory_based/5_atomistic_adiabatic_excited_states/tutorial.ipynb)
  * [6.2.4.2.](6_dynamics/2_nbra_workflows/4_step3/2_build_MB_basis/tutorial.ipynb)

27. Plot the PES of LiH at the EOM-CCSD/sto-3G level computed via interface of Libra with Psi4
  * [8.2.](8_model_hamiltonians/2_interfaces_with_qchem_codes/tutorial.ipynb)

28. Plot the 1D PES of HFCO at the TD-DFTB level compute with interface of Libra with DFTB+
  * [8.2.](8_model_hamiltonians/2_interfaces_with_qchem_codes/tutorial.ipynb)

29. Generate XYZ trajectory from a list of matrices
  * [8.2.](8_model_hamiltonians/2_interfaces_with_qchem_codes/tutorial.ipynb)

30. Perform a ground state adiabatic MD with Libra
  * [6.1.5.](6_dynamics/1_trajectory_based/5_atomistic_adiabatic_excited_states/tutorial.ipynb)
  * [6.1.6.](6_dynamics/1_trajectory_based/6_model_nbra/tutorial.ipynb)
  * [13.2.](13_force_fields_and_classical_md/2_atomistic_Hamiltonian/tutorial.ipynb)

31. Perform an excited state adiabatic MD with Libra
  * [6.1.5.](6_dynamics/1_trajectory_based/5_atomistic_adiabatic_excited_states/tutorial.ipynb)
  * [6.1.6.](6_dynamics/1_trajectory_based/6_model_nbra/tutorial.ipynb)

32. Compute MD with DFTB+ via Libra
  * [6.1.5.](6_dynamics/1_trajectory_based/5_atomistic_adiabatic_excited_states/tutorial.ipynb)

33. Generate XYZ trajectory from HDF5 files
  * [6.1.5.](6_dynamics/1_trajectory_based/5_atomistic_adiabatic_excited_states/tutorial.ipynb)

34. Compute trajectory-averaged dephasing times
  * [6.2.5.1](6_dynamics/2_nbra_workflows/5_step4/1_initialize_data)

35. Compute trajectory-averaged energy gaps
  * [6.2.5.1](6_dynamics/2_nbra_workflows/5_step4/1_initialize_data)

36. Plot trajectory-averaged dephasing times
  * [6.2.5.1](6_dynamics/2_nbra_workflows/5_step4/1_initialize_data)

37. Fit the probability density of randomly distributed point with Gaussian density kernel functions
  * [7.2.](7_special_functions/2_gaussian_kernel_algorithm/tutorial.ipynb)

38. Read the HDF5 files to setup Hamiltonians
  * [6.1.6.](6_dynamics/1_trajectory_based/6_model_nbra/tutorial.ipynb)

39. Read the HDF5 files to plot results of dynamical calculations
  * [6.1.6.](6_dynamics/1_trajectory_based/6_model_nbra/tutorial.ipynb)
  * [6.1.7.](6_dynamics/1_trajectory_based/7_model_nonadiabatic_system_bath/tutorial.ipynb)

40. Compute nonadiabatic dynamics for atomistic systems with NBRA using Kohn-Sham states
  * [6.2.5.1.](6_dynamics/2_nbra_workflows/5_step4/2_dynamics/tutorial.ipynb)

41. Plot the PES profiles with multidimensional model Hamiltonians
  * [6.1.7.](6_dynamics/1_trajectory_based/7_model_nonadiabatic_system_bath/tutorial.ipynb)

42. MD and NAMD in the NVT ensemble
  * [6.1.7.](6_dynamics/1_trajectory_based/7_model_nonadiabatic_system_bath/tutorial.ipynb)

43. Partitioning quantum and classical DOFs
  * [6.1.7.](6_dynamics/1_trajectory_based/7_model_nonadiabatic_system_bath/tutorial.ipynb)

44. Coupling classical DOFs to thermostat
  * [6.1.7.](6_dynamics/1_trajectory_based/7_model_nonadiabatic_system_bath/tutorial.ipynb)

45. Constraining DOFs in dynamics
  * [6.1.7.](6_dynamics/1_trajectory_based/7_model_nonadiabatic_system_bath/tutorial.ipynb)

46. Numerically exact TD-SE
  * [6.4.2.](6_dynamics/4_wavepackets/2_dvr_basics/tutorial.ipynb)
  * [6.4.3.](6_dynamics/4_wavepackets/3_soft_propagation/tutorial.ipynb)
  * [6.4.4.](6_dynamics/4_wavepackets/4_more/Tutorial1.ipynb)
  * [6.4.4.](6_dynamics/4_wavepackets/4_more/Tutorial2.ipynb)
  * [6.4.4.](6_dynamics/4_wavepackets/4_more/Tutorial3.ipynb)
  * [6.4.4.](6_dynamics/4_wavepackets/4_more/Tutorial4.ipynb)

47. DVR calculations
  * [6.4.2.](6_dynamics/4_wavepackets/2_dvr_basics/tutorial.ipynb)
  * [6.4.3.](6_dynamics/4_wavepackets/3_soft_propagation/tutorial.ipynb)
  * [6.4.4.](6_dynamics/4_wavepackets/4_more/Tutorial1.ipynb)
  * [6.4.4.](6_dynamics/4_wavepackets/4_more/Tutorial2.ipynb)
  * [6.4.4.](6_dynamics/4_wavepackets/4_more/Tutorial3.ipynb)
  * [6.4.4.](6_dynamics/4_wavepackets/4_more/Tutorial4.ipynb)

48. Making animated gifs
  * [6.4.3.](6_dynamics/4_wavepackets/3_soft_propagation/tutorial.ipynb)

49. Integrating quantum Liouville's equation of motion
  * [2.2.](2_integrators/2_runge_kutta_4_for_Liouville/tutorial.ipynb)

50. Machine learning with MLP
  * [9.1.](9_machine_learning/1_basics_of_mlp/tutorial.ipynb)
  * [9.2.](9_machine_learning/2_ann_derivatives/tutorial.ipynb)
  * [9.3.](9_machine_learning/3_advanced_ann/tutorial.ipynb)

51. Artificial neural networks (ANN) and error Back Propagation algorithm 
  * [9.1.](9_machine_learning/1_basics_of_mlp/tutorial.ipynb)
  * [9.3.](9_machine_learning/3_advanced_ann/tutorial.ipynb)

52. Derivatives of ANNs
  * [9.2.](9_machine_learning/2_ann_derivatives/tutorial.ipynb)

53. Convert Libra and Python data types
  * [10.1.](10_auxiliary_functions/1_util_functions/tutorial.ipynb)

54. Manipulate vectors (lists of data)
  * [10.1.](10_auxiliary_functions/1_util_functions/tutorial.ipynb)

55. Setup default values of Python dictionary
  * [10.1.](10_auxiliary_functions/1_util_functions/tutorial.ipynb)

56. Interfacing ErgoSCF and Libra
  * [11.1.1.](11_program_specific_methods/1_ergoscf_methods/1_basics/tutorial.ipynb)
  * [11.1.2.](11_program_specific_methods/1_ergoscf_methods/2_nac_workflow/tutorial.ipynb)

57. Sampling random numbers from common distributions
  * [7.4.1.](7_special_functions/4_random_numbers/1_basics/tutorial.ipynb)

58. Sampling random numbers from arbitrary distributions
  * [7.4.1.](7_special_functions/4_random_numbers/1_basics/tutorial.ipynb)
  * [7.4.2.](7_special_functions/4_random_numbers/2_metropolis/tutorial.ipynb)

59. Computing data probability densities and cumulative distribution functions
  * [7.3.](7_special_functions/3_data_statistics/tutorial.ipynb) 
  * [7.4.1.](7_special_functions/4_random_numbers/1_basics/tutorial.ipynb) 
  * [7.4.2.](7_special_functions/4_random_numbers/2_metropolis/tutorial.ipynb)
  * [11.2.2.](11_program_specific_methods/2_qe_methods/2_md/1_co2/tutorial.ipynb)

60. Generating (deterministic) quasi-random numbers
  * [7.4.1.](7_special_functions/4_random_numbers/1_basics/tutorial.ipynb)
  * [7.4.2.](7_special_functions/4_random_numbers/2_metropolis/tutorial.ipynb)

61. Dynamical regimes and chaotic systems
  * [7.4.1.](7_special_functions/4_random_numbers/1_basics/tutorial.ipynb)

62. Wigner sampling
  * [7.4.2.](7_special_functions/4_random_numbers/2_metropolis/tutorial.ipynb)

63. Canonical and microcanonical enesemble sampling
  * [7.4.2.](7_special_functions/4_random_numbers/2_metropolis/tutorial.ipynb)

64. Analyzing MD trajectories
  * [11.2.2.](11_program_specific_methods/2_qe_methods/2_md/1_co2/tutorial.ipynb)

65. Normal modes
  * [11.2.3.](11_program_specific_methods/2_qe_methods/3_normal_modes/tutorial.ipynb)

66. Constructing quantum dots
  * [12.1.](12_molecular_builders/1_crystal_and_qd_builder/tutorial.ipynb)

67. Constructing periodic structures
  * [12.1.](12_molecular_builders/1_crystal_and_qd_builder/tutorial.ipynb)
  * [12.2.1.](12_molecular_builders/2_chemobjects/1_basic_construction_and_manipulaiton/tutorial.ipynb)

68. Automatically determining connectivity in complex structures
  * [12.1.](12_molecular_builders/1_crystal_and_qd_builder/tutorial.ipynb)

69. Computing NACs using ErgoSCF/Libra
  * [11.1.2.](11_program_specific_methods/1_ergoscf_methods/2_nac_workflow/tutorial.ipynb)

70. Computing NACs using DFTB+/Libra
  * [6.2.4.1.](6_dynamics/2_nbra_workflows/4_step3/1_build_SP_basis/tutorial.ipynb)
  * [6.2.4.2.](6_dynamics/2_nbra_workflows/4_step3/2_build_MB_basis/tutorial.ipynb)

71. Computing NACs using CP2K/Libra
  * [6.2.4.1.](6_dynamics/2_nbra_workflows/4_step3/1_build_SP_basis/tutorial.ipynb)
  * [6.2.4.2.](6_dynamics/2_nbra_workflows/4_step3/2_build_MB_basis/tutorial.ipynb)

72. Computing single-particle (KS-DFT, HF, semiempirical) NACs 
  * [6.2.3.](6_dynamics/2_nbra_workflows/3_step2_qe/tutorial.ipynb)
  * [6.2.4.1.](6_dynamics/2_nbra_workflows/4_step3/1_build_SP_basis/tutorial.ipynb)
  * [11.1.2.](11_program_specific_methods/1_ergoscf_methods/2_nac_workflow/tutorial.ipynb)

73. Computing many-body (TD-DFT, TD-DFTB, CI) NACs 
  * [6.2.4.2.](6_dynamics/2_nbra_workflows/4_step3/2_build_MB_basis/tutorial.ipynb)

74. Saving ANNs to files and creating ANNs from XML files
  * [9.1.](9_machine_learning/1_basics_of_mlp/tutorial.ipynb)
  * [9.3.](9_machine_learning/3_advanced_ann/tutorial.ipynb)

75. Rprop algorithm for ANN training 
  * [9.3.](9_machine_learning/3_advanced_ann/tutorial.ipynb)

76. Momentum algorithm in the ANN training 
  * [9.3.](9_machine_learning/3_advanced_ann/tutorial.ipynb)

77. Weight decay in the ANN training 
  * [9.3.](9_machine_learning/3_advanced_ann/tutorial.ipynb)

78. Rotating and translating molecular fragments
  * [12.2.1.](12_molecular_builders/2_chemobjects/1_basic_construction_and_manipulation/tutorial.ipynb)
  * [12.2.2.](12_molecular_builders/2_chemobjects/2_extended_rotation_and_translation/tutorial.ipynb)

79. Creating classical force fields 
  * [13.1.](13_force_fields_and_classical_md/1_force_field_basics/tutorial.ipynb)
  * [13.2.](13_force_fields_and_classical_md/2_atomistic_Hamiltonian/tutorial.ipynb)

80. Molecular mechanics calculations (Hamiltonian_Atomistic)
  * [13.2.](13_force_fields_and_classical_md/2_atomistic_Hamiltonian/tutorial.ipynb)
  * [13.3.](13_force_fields_and_classical_md/3_mm_optimization/tutorial.ipynb)

81. Mixing force fields
  * [13.2.](13_force_fields_and_classical_md/2_atomistic_Hamiltonian/tutorial.ipynb)

82. NVE ensemble MD with force fields
  * [13.2.](13_force_fields_and_classical_md/2_atomistic_Hamiltonian/tutorial.ipynb)

83. Simulated annealing
  * [13.3.](13_force_fields_and_classical_md/3_mm_optimization/tutorial.ipynb)

84. Molecular mechanics molecular structure optimization
  * [13.3.](13_force_fields_and_classical_md/3_mm_optimization/tutorial.ipynb)


_______________________________


## Functions

- `liblibra::libconverters`
  - `Py2Cpp_int` [10.1.](10_auxiliary_functions/1_util_functions/tutorial.ipynb)
  - `Py2Cpp_double` [10.1.](10_auxiliary_functions/1_util_functions/tutorial.ipynb)
  - `Py2Cpp_complex` [10.1.](10_auxiliary_functions/1_util_functions/tutorial.ipynb)
  - `Py2Cpp_string` [10.1.](10_auxiliary_functions/1_util_functions/tutorial.ipynb)
  - `Py2Cpp_VECTOR` [10.1.](10_auxiliary_functions/1_util_functions/tutorial.ipynb)
  - `Py2Cpp_MATRIX` [10.1.](10_auxiliary_functions/1_util_functions/tutorial.ipynb)
  - `Py2Cpp_CMATRIX` [10.1.](10_auxiliary_functions/1_util_functions/tutorial.ipynb)
  - `Cpp2Py` [10.1.](10_auxiliary_functions/1_util_functions/tutorial.ipynb)

- `liblibra::libdyn`
  - `libgwp`
    - `gwp_coupling` [6.4.1.1.](6_dynamics/4_wavepackets/1_gaussian/1_matrix_elements/tutorial.ipynb)
    - `gwp_dipole` [6.4.1.1.](6_dynamics/4_wavepackets/1_gaussian/1_matrix_elements/tutorial.ipynb)
    - `gwp_kinetic` [6.4.1.1.](6_dynamics/4_wavepackets/1_gaussian/1_matrix_elements/tutorial.ipynb)
    - `gwp_overlap` [6.4.1.1.](6_dynamics/4_wavepackets/1_gaussian/1_matrix_elements/tutorial.ipynb)
    - `gwp_value` [6.4.1.1.](6_dynamics/4_wavepackets/1_gaussian/1_matrix_elements/tutorial.ipynb)
  - `libwfcgrid`
    - `compute_imapping`[6.4.2.](6_dynamics/4_wavepackets/2_dvr_basics/tutorial.ipynb)
    - `compute_mapping` [6.4.2.](6_dynamics/4_wavepackets/2_dvr_basics/tutorial.ipynb)

- `liblibra::libintegrators`
  - `RK4` [2.1.](2_integrators/1_runge_kutta_4th_order/tutorial.ipynb) | [2.2.](2_integrators/2_runge_kutta_4_for_Liouville/tutorial.ipynb)

- `liblibra::liblinalg`
  - `pop_submatrix` [9.1.](9_machine_learning/1_basics_of_mlp/tutorial.ipynb)

- `liblibra::libmontecarlo`
  - `metropolis_gau` [7.4.2.](7_special_functions/4_random_numbers/2_metropolis/tutorial.ipynb)

- `liblibra::libspecialfunctions`
  - `randperm` [9.1.](9_machine_learning/1_basics_of_mlp/tutorial.ipynb)

- `liblibra::libqm_tools`
  - `charge_density` [5.1.1.](5_electronic_structure/1_eht/1_compact/tutorial.ipynb)
  - `compute_dos` [5.1.1.](5_electronic_structure/1_eht/1_compact/tutorial.ipynb)

- `liblibra::libpot`
  - `Angle_Cubic` [13.1.](13_force_fields_and_classical_md/1_force_field_basics/tutorial.ipynb)
  - `Angle_Fourier` [13.1.](13_force_fields_and_classical_md/1_force_field_basics/tutorial.ipynb)
  - `Angle_Fourier_General` [13.1.](13_force_fields_and_classical_md/1_force_field_basics/tutorial.ipynb)
  - `Angle_Fourier_Special` [13.1.](13_force_fields_and_classical_md/1_force_field_basics/tutorial.ipynb)
  - `Angle_Harmonic` [13.1.](13_force_fields_and_classical_md/1_force_field_basics/tutorial.ipynb)
  - `Angle_Harmonic_Cos` [13.1.](13_force_fields_and_classical_md/1_force_field_basics/tutorial.ipynb)
  - `Angle_Harmonic_Cos_General` [13.1.](13_force_fields_and_classical_md/1_force_field_basics/tutorial.ipynb)
  - `Bond_Harmonic` [13.1.](13_force_fields_and_classical_md/1_force_field_basics/tutorial.ipynb)
  - `Bond_Quartic` [13.1.](13_force_fields_and_classical_md/1_force_field_basics/tutorial.ipynb)
  - `Bond_Morse` [13.1.](13_force_fields_and_classical_md/1_force_field_basics/tutorial.ipynb)
  - `Dihedral_Fourier` [13.1.](13_force_fields_and_classical_md/1_force_field_basics/tutorial.ipynb)
  - `Dihedral_General` [13.1.](13_force_fields_and_classical_md/1_force_field_basics/tutorial.ipynb)
  - `Elec_Coulomb` [13.1.](13_force_fields_and_classical_md/1_force_field_basics/tutorial.ipynb)
  - `Elec_Ewald3D` [13.1.](13_force_fields_and_classical_md/1_force_field_basics/tutorial.ipynb)
  - `Gay_Berne` [13.1.](13_force_fields_and_classical_md/1_force_field_basics/tutorial.ipynb)
  - `Girifalco12_6` [13.1.](13_force_fields_and_classical_md/1_force_field_basics/tutorial.ipynb)
  - `LJ_Coulomb` [13.1.](13_force_fields_and_classical_md/1_force_field_basics/tutorial.ipynb)
  - `OOP_Fourier` [13.1.](13_force_fields_and_classical_md/1_force_field_basics/tutorial.ipynb)
  - `OOP_Harmonic` [13.1.](13_force_fields_and_classical_md/1_force_field_basics/tutorial.ipynb)
  - `OOP_Wilson` [13.1.](13_force_fields_and_classical_md/1_force_field_basics/tutorial.ipynb)
  - `Stretch_Bend_Harmonic` [13.1.](13_force_fields_and_classical_md/1_force_field_basics/tutorial.ipynb)
  - `Vdw_Buffered14_7` [13.1.](13_force_fields_and_classical_md/1_force_field_basics/tutorial.ipynb)
  - `VdW_Ewald3D` [13.1.](13_force_fields_and_classical_md/1_force_field_basics/tutorial.ipynb)
  - `Vdw_LJ` [13.1.](13_force_fields_and_classical_md/1_force_field_basics/tutorial.ipynb)
  - `Vdw_LJ1` [13.1.](13_force_fields_and_classical_md/1_force_field_basics/tutorial.ipynb)
  - `Vdw_LJ2_excl` [13.1.](13_force_fields_and_classical_md/1_force_field_basics/tutorial.ipynb)
  - `Vdw_LJ2_no_excl` [13.1.](13_force_fields_and_classical_md/1_force_field_basics/tutorial.ipynb)
  - `Vdw_Morse` [13.1.](13_force_fields_and_classical_md/1_force_field_basics/tutorial.ipynb)

- `libra_py`
  - `autoconnect`
    - `autoconnect` [12.1.](12_molecular_builders/1_crystal_and_qd_builder/tutorial.ipynb)
    - `find_undercoordinated_atoms` [12.1.](12_molecular_builders/1_crystal_and_qd_builder/tutorial.ipynb)

  - `build`
    - `make_xyz_mat` [11.2.2.](11_program_specific_methods/2_qe_methods/2_md/1_co2/tutorial.ipynb)
    - `read_xyz` [12.1.](12_molecular_builders/1_crystal_and_qd_builder/tutorial.ipynb)
    - `make_xyz` [12.1.](12_molecular_builders/1_crystal_and_qd_builder/tutorial.ipynb)
    - `read_xyz_crystal` [12.1.](12_molecular_builders/1_crystal_and_qd_builder/tutorial.ipynb)
    - `generate_replicas_xyz` [12.1.](12_molecular_builders/1_crystal_and_qd_builder/tutorial.ipynb)
    - `generate_replicas_xyz2` [12.1.](12_molecular_builders/1_crystal_and_qd_builder/tutorial.ipynb)
    - `crop_sphere_xyz` [12.1.](12_molecular_builders/1_crystal_and_qd_builder/tutorial.ipynb)
    - `crop_sphere_xyz2` [12.1.](12_molecular_builders/1_crystal_and_qd_builder/tutorial.ipynb)
    - `crop_sphere_xyz3` [12.1.](12_molecular_builders/1_crystal_and_qd_builder/tutorial.ipynb)
    - `add_atom_to_system` [12.1.](12_molecular_builders/1_crystal_and_qd_builder/tutorial.ipynb)
    - `add_atoms_to_system` [12.1.](12_molecular_builders/1_crystal_and_qd_builder/tutorial.ipynb)

  - `CP2K_methods`
    - `cp2k_distribute`
    - `cp2k_find_excitation_energies`
    - `CP2K_input_static`
    - `cp2k_xtb_diag_inp`
    - `cp2k_xtb_ot_inp`
    - `cube_file_names_cp2k`
    - `distribute_cp2k_libint_jobs`
    - `extract_coordinates`
    - `find_basis_set`
    - `generate_translational_vectors`
    - `index_reorder`
    - `make_shell`
    - `molog_lvals`
    - `read_ao_matrices`
    - `read_cp2k_tddfpt_log_file`
    - `read_energies_from_cp2k_log_file`
    - `read_energies_from_cp2k_md_log_file`
    - `read_homo_index`
    - `read_molog_file`
    - `read_trajectory_xyz_file`
    - `resort_molog_eigenvectors`
    - `run_cp2k_xtb`

  - `dynamics`
    - `heom`
      - `compute` 
        - `run_dynamics` [6.3.1.](6_dynamics/3_heom/1_dynamics_and_lineshapes/tutorial.ipynb)
    - `tsh`
      - `compute`
        - `generic_recipe` [6.1.6.](6_dynamics/1_trajectory_based/6_model_nbra/tutorial.ipynb) | 
            [6.1.7.](6_dynamics/1_trajectory_based/7_model_nonadiabatic_system_bath/tutorial.ipynb)
        - `init_electronic_dyn_var` [6.1.5.](6_dynamics/1_trajectory_based/5_atomistic_adiabatic_excited_states/tutorial.ipynb) 
        - `init_nuclear_dyn_var` [6.1.5.](6_dynamics/1_trajectory_based/5_atomistic_adiabatic_excited_states/tutorial.ipynb) |
            [6.1.6.](6_dynamics/1_trajectory_based/6_model_nbra/tutorial.ipynb) |
            [6.1.7.](6_dynamics/1_trajectory_based/7_model_nonadiabatic_system_bath/tutorial.ipynb)
        - `run_dynamics` [6.1.5.](6_dynamics/1_trajectory_based/5_atomistic_adiabatic_excited_states/tutorial.ipynb)
      - `plot`
        - `add_basis_transform` [6.1.6.](6_dynamics/1_trajectory_based/6_model_nbra/tutorial.ipynb)
        - `add_coordinates_vs_t` [6.1.6.](6_dynamics/1_trajectory_based/6_model_nbra/tutorial.ipynb)
        - `add_energies` [6.1.6.](6_dynamics/1_trajectory_based/6_model_nbra/tutorial.ipynb)
        - `add_momentum_vs_t` [6.1.6.](6_dynamics/1_trajectory_based/6_model_nbra/tutorial.ipynb)
        - `add_phase_space` [6.1.6.](6_dynamics/1_trajectory_based/6_model_nbra/tutorial.ipynb)
        - `add_populations` [6.1.6.](6_dynamics/1_trajectory_based/6_model_nbra/tutorial.ipynb)
        - `add_time_overlap_projectors` [6.1.6.](6_dynamics/1_trajectory_based/6_model_nbra/tutorial.ipynb)
        - `add_trajectory_resolved_ham_property` [6.1.6.](6_dynamics/1_trajectory_based/6_model_nbra/tutorial.ipynb)
        - `hdf2xyz` [6.1.5.](6_dynamics/1_trajectory_based/5_atomistic_adiabatic_excited_states/tutorial.ipynb)
        - `plot_dyn` [6.1.5.](6_dynamics/1_trajectory_based/5_atomistic_adiabatic_excited_states/tutorial.ipynb)
        - `plot_dynamics` [6.1.6.](6_dynamics/1_trajectory_based/6_model_nbra/tutorial.ipynb) |
            [6.1.7.](6_dynamics/1_trajectory_based/7_model_nonadiabatic_system_bath/tutorial.ipynb)
      - `recipes`
        - `adiabatic_md_interfaces_params` [6.1.5.](6_dynamics/1_trajectory_based/5_atomistic_adiabatic_excited_states/tutorial.ipynb)

  - `molden_methods`
    - `eigenvectors_molden`
    - `index_reorder`
    - `molden_file_to_libint_shell`
    - `resort_eigenvectors`

  - `models`
    - `Holstein`
      - `Holstein2` [6.1.6.](6_dynamics/1_trajectory_based/6_model_nbra/tutorial.ipynb) | 
            [6.4.3.](6_dynamics/4_wavepackets/3_soft_propagation/tutorial.ipynb)
    - `Martens` 
      - `model1` [6.4.3.](6_dynamics/4_wavepackets/3_soft_propagation/tutorial.ipynb)
      - `model2` [6.4.3.](6_dynamics/4_wavepackets/3_soft_propagation/tutorial.ipynb)
    - `Tully`
      - `chain_potential` [6.1.7.](6_dynamics/1_trajectory_based/7_model_nonadiabatic_system_bath/tutorial.ipynb)

  - `workflows`
    - `nbra`
      - `compute_hprime`
        - `compute_hprime_dia`
        - `hprime_py`
      - `compute_properties`
        - `compute_properties_onekpt`
      - `decoherence_times`
        - `decoherence_times2rates`
        - `energy_gaps`
        - `energy_gaps_ave` [6.2.3.](/6_dynamics/2_nbra_workflows/5_step4/1_initialize_data/tutorial.ipynb)
        - `decoherence_times`
        - `decoherence_times_ave_old`
        - `decoherence_times_ave` [6.2.3.](/6_dynamics/2_nbra_workflows/5_step4/1_initialize_data/tutorial.ipynb)
      - `lz`
        - `Belyaev_Lebedev`
        - `adjust_SD_probabilities`
        - `run`
      - `mapping`
        - `sd2indx`
        - `energy_arb`
        - `energy_mat_arb`
        - `orbs2spinorbs`
        - `ovlp_arb`
        - `ovlp_mat_arb` [6.2.4.2.](6_dynamics/2_nbra_workflows/4_step3/2_build_MB_basis/tutorial.ipynb)
      - `qsh`
        - `compute_freqs`
        - `compute_qs_Hvib`
        - `run`
      - `step2`
        - `run` [6.2.3.](6_dynamics/2_nbra_workflows/3_step2_qe/tutorial.ipynb)
        - `run_cp2k_libint_step2` [6.2.7.](6_dynamics/2_nbra_workflows/7_step2_cp2k)
      - `step2_analysis`
        - `compute_oscillator_strengths`
        - `compute_spectrum`
        - `get_step2_mb_sp_properties`
      - `step2_dftb`
        - `do_step`
        - `do_ovlp`
        - `run_step2`
        - `run_step2_lz`
      - `step2_ergoscf`
        - `do_step`
        - `do_ovlp`
        - `clean`
        - `run_step2` [11.1.2.](11_program_specific_methods/1_ergoscf_methods/2_nac_workflow/tutorial.ipynb)
      - `step2_many_body`
        - `curr_and_final_step_job`
        - `normalize_ci_coefficients`
        - `get_excitation_analysis_output`
        - `integrate_cube_set`
        - `compute_cube_ks_overlaps`
        - `reindex_cp2k_sd_states` [6.2.4.2.](6_dynamics/2_nbra_workflows/4_step3/2_build_MB_basis/tutorial.ipynb)
        - `form_Hvib_real`
        - `run_step2_many_body`
      - `step3`
        - `apply_normalization` [6.2.4.2.](6_dynamics/2_nbra_workflows/4_step3/2_build_MB_basis/tutorial.ipynb)
        - `apply_orthonormalization_general [6.2.4.2.](6_dynamics/2_nbra_workflows/4_step3/2_build_MB_basis/tutorial.ipynb)
        - `apply_orthonormalization_scipy`
        - `apply_phase_correction`
        - `apply_phase_correction_general` [6.2.4.2.](6_dynamics/2_nbra_workflows/4_step3/2_build_MB_basis/tutorial.ipynb)
        - `apply_phase_correction_scipy` 
        - `apply_state_reordering` [6.2.4.2.](6_dynamics/2_nbra_workflows/4_step3/2_build_MB_basis/tutorial.ipynb)
        - `apply_state_reordering_general` [6.2.4.2.](6_dynamics/2_nbra_workflows/4_step3/2_build_MB_basis/tutorial.ipynb)
        - `build_SD_basis` [6.2.4.1.](6_dynamics/2_nbra_workflows/4_step3/1_build_SD_basis/tutorial.ipynb)
        - `compute_Hvib`
        - `compute_phase_corrections_scipy`
        - `do_phase_corr`
        - `do_phase_corr_scipy`
        - `get_Lowdin`
        - `get_Lowdin_general`
        - `get_Lowdin_scipy`
        - `get_step2_data` [6.2.4.1.](6_dynamics/2_nbra_workflows/4_step3/1_build_SD_basis/tutorial.ipynb) | [6.2.4.2.](6_dynamics/2_nbra_workflows/4_step3/2_build_MB_basis/tutorial.ipynb)
        - `make_cost_mat`
        - `map_Hvib`
        - `orthonormalize_ks_overlaps`
        - `output_sorted_Hvibs` [6.2.4.1.](6_dynamics/2_nbra_workflows/4_step3/1_build_SD_basis/tutorial.ipynb)
        - `print_SD_basis` [6.2.4.1.](6_dynamics/2_nbra_workflows/4_step3/1_build_SD_basis/tutorial.ipynb)
        - `pyxaid2libra`
        - `run` [6.2.4.1.](6_dynamics/2_nbra_workflows/4_step3/1_build_SD_basis/tutorial.ipynb)
        - `run_step3_ks_nacs_libint` [6.2.8.](6_dynamics/2_nbra_workflows/8_step3_cp2k)
        - `run_step3_sd_nacs_libint` [6.2.8.](6_dynamics/2_nbra_workflows/8_step3_cp2k)
        - `sac_matrices`
        - `scale_H_vib`
        - `sort_SD_energies` [6.2.4.1.](6_dynamics/2_nbra_workflows/4_step3/1_build_SD_basis/tutorial.ipynb)
        - `sort_unique_SD_basis` [6.2.4.2.](6_dynamics/2_nbra_workflows/4_step3/2_build_MB_basis/tutorial.ipynb)
        - `sort_unique_SD_basis_scipy`
      - `step3_many_body`
        - `get_step2_mb_sp_properties` [6.2.4.2.](6_dynamics/2_nbra_workflows/4_step3/2_build_MB_basis/tutorial.ipynb)
        - `compute_ci_energies_midpoint` [6.2.4.2.](6_dynamics/2_nbra_workflows/4_step3/2_build_MB_basis/tutorial.ipynb)
        - `make_T_matrices` [6.2.4.2.](6_dynamics/2_nbra_workflows/4_step3/2_build_MB_basis/tutorial.ipynb)
        - `run` [6.2.4.2.](6_dynamics/2_nbra_workflows/4_step3/2_build_MB_basis/tutorial.ipynb)
      - `step4`
        - `get_Hvib`
        - `get_Hvib2` [6.2.5.1.](/6_dynamics/2_nbra_workflows/5_step4/1_initialize_data/tutorial.ipynb)
        - `traj_statistics`
        - `traj_statistics2`
        - `traj_statistics2_fast`
        - `printout`
        - `run` [6.2.5.1.](/6_dynamics/2_nbra_workflows/5_step4/1_initialize_data/tutorial.ipynb)

  - `data_conv`
    - `make_list` [6.1.5.](6_dynamics/1_trajectory_based/5_atomistic_adiabatic_excited_states/tutorial.ipynb)
    - `matrix2list` [6.1.5.](6_dynamics/1_trajectory_based/5_atomistic_adiabatic_excited_states/tutorial.ipynb)
    - `MATRIX2nparray` [9.2.](9_machine_learning/2_ann_derivatives/tutorial.ipynb) |
        [11.2.1.](11_program_specific_methods/2_qe_methods/1_pdos/tutorial.ipynb) | 
        [6.2.5.1.](/6_dynamics/2_nbra_workflows/5_step4/1_initialize_data/tutorial.ipynb)
    - `nparray2CMATRIX` [6.2.4.1.](6_dynamics/2_nbra_workflows/4_step3/1_build_SD_basis/tutorial.ipynb)

  - `data_outs`
    - `print_matrix` [6.1.5.](6_dynamics/1_trajectory_based/5_atomistic_adiabatic_excited_states/tutorial.ipynb) |
        [9.2.](9_machine_learning/2_ann_derivatives/tutorial.ipynb) | [11.1.1.](11_program_specific_methods/1_ergoscf_methods/1_basics/tutorial.ipynb) |
        [6.2.4.1.](6_dynamics/2_nbra_workflows/4_step3/1_build_SD_basis/tutorial.ipynb)

  - `data_read`
    - `get_data_sets` [6.2.3.](6_dynamics/2_nbra_workflows/3_step2_qe/tutorial.ipynb)
    - `read_2D_grid` [6.4.3.](6_dynamics/4_wavepackets/3_soft_propagation/tutorial.ipynb)

  - `data_stat`
    - `cmat_stat2` [6.2.3.](6_dynamics/2_nbra_workflows/3_step2_qe/tutorial.ipynb) |
         [6.2.4.1.](6_dynamics/2_nbra_workflows/4_step3/1_build_SD_basis/tutorial.ipynb) |
         [6.2.4.2.](6_dynamics/2_nbra_workflows/4_step3/2_build_MB_basis/tutorial.ipynb)

  - `data_visualize`
    - `colors` [7.2.](7_special_functions/2_gaussian_kernel_algorithm/tutorial.ipynb)
    - `plot_map` [6.4.1.1.](6_dynamics/4_wavepackets/1_gaussian/1_matrix_elements/tutorial.ipynb) | 
      [6.4.3.](6_dynamics/4_wavepackets/3_soft_propagation/tutorial.ipynb) |
      [9.2.](9_machine_learning/2_ann_derivatives/tutorial.ipynb) |
      [9.3.](9_machine_learning/3_advanced_ann/tutorial.ipynb)
    - `plot_map_nparray` [6.2.5.1](6_dynamics/2_nbra_workflows/5_step4/1_initialize_data)

  - `DFTB_methods`
    - `read_dftb_output` [8.2.](8_model_hamiltonians/2_interfaces_with_qchem_codes/tutorial.ipynb)
    - `run_dftb_adi` [8.2.](8_model_hamiltonians/2_interfaces_with_qchem_codes/tutorial.ipynb) | 
       [6.1.5.](6_dynamics/1_trajectory_based/5_atomistic_adiabatic_excited_states/tutorial.ipynb)
    - `make_dftb_input` [8.2.](8_model_hamiltonians/2_interfaces_with_qchem_codes/tutorial.ipynb)

  - `dynamics_plotting`
    - `plot_pes_properties` [8.1.](8_model_hamiltonians/1_pes_plotting/tutorial.ipynb) | [8.2.](8_model_hamiltonians/2_interfaces_with_qchem_codes/tutorial.ipynb)
    - `plot_surfaces` [8.1.](8_model_hamiltonians/1_pes_plotting/tutorial.ipynb) | 
            [6.1.6.](6_dynamics/1_trajectory_based/6_model_nbra/tutorial.ipynb) |
            [6.1.7.](6_dynamics/1_trajectory_based/7_model_nonadiabatic_system_bath/tutorial.ipynb) | 
            [6.4.3.](6_dynamics/4_wavepackets/3_soft_propagation/tutorial.ipynb)

  - `ERGO_methods`
    - `get_mtx_matrices` [11.1.1.](11_program_specific_methods/1_ergoscf_methods/1_basics/tutorial.ipynb)
    - `read_mo_restricted` [11.1.1.](11_program_specific_methods/1_ergoscf_methods/1_basics/tutorial.ipynb)
    - `read_mo_unrestricted` [11.1.1.](11_program_specific_methods/1_ergoscf_methods/1_basics/tutorial.ipynb)
    - `read_spectrum_restricted` [11.1.1.](11_program_specific_methods/1_ergoscf_methods/1_basics/tutorial.ipynb)
    - `read_spectrum_unrestricted` [11.1.1.](11_program_specific_methods/1_ergoscf_methods/1_basics/tutorial.ipynb)

  - `ft`
    - `ft2`[6.3.1.](6_dynamics/3_heom/1_dynamics_and_lineshapes/tutorial.ipynb)

  - `gaussian_kernel_algorithm`
    - `compute_apriory_prob_densities_1D` [7.2.](7_special_functions/2_gaussian_kernel_algorithm/tutorial.ipynb)
    - `compute_widths_1D` [7.2.](7_special_functions/2_gaussian_kernel_algorithm/tutorial.ipynb)
    - `gaussian_density_estimator_1D` [7.2.](7_special_functions/2_gaussian_kernel_algorithm/tutorial.ipynb)
    - `gaussian_kernel_algorithm_iteration_1D` [7.2.](7_special_functions/2_gaussian_kernel_algorithm/tutorial.ipynb)

  - `hpc_utils`
    - `distribute` [6.2.3.](6_dynamics/2_nbra_workflows/3_step2_qe/tutorial.ipynb)

  - `LoadGAFF`
    - `Load_GAFF` [13.1.](13_force_fields_and_classical_md/1_force_field_basics/tutorial.ipynb)

  - `LoadGAFF`
    - `Load_MMFF94` [13.1.](13_force_fields_and_classical_md/1_force_field_basics/tutorial.ipynb)

  - `LoadMolecule`
    - `Load_Molecule` [5.1.1.](5_electronic_structure/1_eht/1_compact/tutorial.ipynb) | 
                      [12.2.1.](12_molecular_builders/2_chemobjects/1_basic_construction_and_manipulation/tutorial.ipynb) |
                      [12.2.2.](12_molecular_builders/2_chemobjects/2_extended_rotation_and_translation/tutorial.ipynb)
   
  - `LoadPT`
    - `Load_PT` [5.1.1.](5_electronic_structure/1_eht/1_compact/tutorial.ipynb) | 
                [12.2.1.](12_molecular_builders/2_chemobjects/1_basic_construction_and_manipulation/tutorial.ipynb) |
                [12.2.2.](12_molecular_builders/2_chemobjects/2_extended_rotation_and_translation/tutorial.ipynb)

  - `LoadTRIPOS`
    - `Load_TRIPOS` [13.1.](13_force_fields_and_classical_md/1_force_field_basics/tutorial.ipynb)

  - `LoadUFF`
    - `Load_UFF` [13.1.](13_force_fields_and_classical_md/1_force_field_basics/tutorial.ipynb)

  - `normal_modes`
    - `get_xyz2` [11.2.3.](11_program_specific_methods/2_qe_methods/3_normal_modes/tutorial.ipynb) 

  - `nve_md`
    - `nve_md_init` [13.2.](13_force_fields_and_classical_md/2_atomistic_Hamiltonian/tutorial.ipynb)
    - `nve_md_step` [13.2.](13_force_fields_and_classical_md/2_atomistic_Hamiltonian/tutorial.ipynb)
    - `optimize_syst` [13.3.](13_force_fields_and_classical_md/3_mm_optimization/tutorial.ipynb)
    - `syst2xyz` [13.3.](13_force_fields_and_classical_md/3_mm_optimization/tutorial.ipynb)
    
  - `pdos`
    - `libra_pdos` [5.1.1.](5_electronic_structure/1_eht/1_compact/tutorial.ipynb)
    - `QE_pdos` [11.2.1.](11_program_specific_methods/2_qe_methods/1_pdos/tutorial.ipynb)

  - `psi4_methods`
    - `run_psi4_adi` [8.2.](8_model_hamiltonians/2_interfaces_with_qchem_codes/tutorial.ipynb)

  - `QE_methods`
    - `out2inp` [6.2.3.](6_dynamics/2_nbra_workflows/3_step2_qe/tutorial.ipynb)
    - `read_md_data` [11.2.2.](11_program_specific_methods/2_qe_methods/2_md/1_co2/tutorial.ipynb)
    - `read_md_data_cell` [11.2.2.](11_program_specific_methods/2_qe_methods/2_md/1_co2/tutorial.ipynb)
    - `get_QE_normal_modes` [11.2.3.](11_program_specific_methods/2_qe_methods/3_normal_modes/tutorial.ipynb) 
        
  - `scan`
    - `coords2xyz` [8.2.](8_model_hamiltonians/2_interfaces_with_qchem_codes/tutorial.ipynb)
    - `make_path_xyz2` [8.2.](8_model_hamiltonians/2_interfaces_with_qchem_codes/tutorial.ipynb)

- `liblibra::libutil`
  - `allocate_1D` [10.1.](10_auxiliary_functions/1_util_functions/tutorial.ipynb)
  - `allocate_2D` [10.1.](10_auxiliary_functions/1_util_functions/tutorial.ipynb)
  - `allocate_3D` [10.1.](10_auxiliary_functions/1_util_functions/tutorial.ipynb)
  - `show_vector` [10.1.](10_auxiliary_functions/1_util_functions/tutorial.ipynb)
  - `is_in_vector` [10.1.](10_auxiliary_functions/1_util_functions/tutorial.ipynb)
  - `is_repeating` [10.1.](10_auxiliary_functions/1_util_functions/tutorial.ipynb)
  - `delta` [10.1.](10_auxiliary_functions/1_util_functions/tutorial.ipynb)
  - `split_line` [10.1.](10_auxiliary_functions/1_util_functions/tutorial.ipynb)
  - `is_equal` [10.1.](10_auxiliary_functions/1_util_functions/tutorial.ipynb)
  - `is_included` [10.1.](10_auxiliary_functions/1_util_functions/tutorial.ipynb)
  - `is_present` [10.1.](10_auxiliary_functions/1_util_functions/tutorial.ipynb)
  - `check_input` [10.1.](10_auxiliary_functions/1_util_functions/tutorial.ipynb)

_______________________________


## Classes and class members


- `liblibra::libann`
  - `NeuralNetwork` [9.1.](9_machine_learning/1_basics_of_mlp/tutorial.ipynb) | [9.2.](9_machine_learning/2_ann_derivatives/tutorial.ipynb) | [9.3.](9_machine_learning/3_advanced_ann/tutorial.ipynb)
    - `Nlayers` [9.1.](9_machine_learning/1_basics_of_mlp/tutorial.ipynb)
    - `Npe` [9.1.](9_machine_learning/1_basics_of_mlp/tutorial.ipynb)
    - `W` [9.1.](9_machine_learning/1_basics_of_mlp/tutorial.ipynb)
    - `dW` [9.1.](9_machine_learning/1_basics_of_mlp/tutorial.ipynb)
    - `dWold` [9.1.](9_machine_learning/1_basics_of_mlp/tutorial.ipynb)
    - `grad_w` [9.1.](9_machine_learning/1_basics_of_mlp/tutorial.ipynb)
    - `grad_w_old` [9.1.](9_machine_learning/1_basics_of_mlp/tutorial.ipynb)
    - `B` [9.1.](9_machine_learning/1_basics_of_mlp/tutorial.ipynb)
    - `dB` [9.1.](9_machine_learning/1_basics_of_mlp/tutorial.ipynb)
    - `dBold` [9.1.](9_machine_learning/1_basics_of_mlp/tutorial.ipynb)
    - `grad_b` [9.1.](9_machine_learning/1_basics_of_mlp/tutorial.ipynb)
    - `grad_b_old` [9.1.](9_machine_learning/1_basics_of_mlp/tutorial.ipynb)
    - `propagate` [9.1.](9_machine_learning/1_basics_of_mlp/tutorial.ipynb) | [9.2.](9_machine_learning/2_ann_derivatives/tutorial.ipynb) | [9.3.](9_machine_learning/3_advanced_ann/tutorial.ipynb)
    - `derivatives` [9.2.](9_machine_learning/2_ann_derivatives/tutorial.ipynb)
    - `back_propagate` [9.1.](9_machine_learning/1_basics_of_mlp/tutorial.ipynb)
    - `init_weights_biases_uniform` [9.1.](9_machine_learning/1_basics_of_mlp/tutorial.ipynb) | [9.2.](9_machine_learning/2_ann_derivatives/tutorial.ipynb) | [9.3.](9_machine_learning/3_advanced_ann/tutorial.ipynb)
    - `init_weights_biases_normal` [9.1.](9_machine_learning/1_basics_of_mlp/tutorial.ipynb)
    - `train` [9.1.](9_machine_learning/1_basics_of_mlp/tutorial.ipynb) | [9.2.](9_machine_learning/2_ann_derivatives/tutorial.ipynb) | [9.3.](9_machine_learning/3_advanced_ann/tutorial.ipynb)
    - `load` [9.1.](9_machine_learning/1_basics_of_mlp/tutorial.ipynb)
    - `save` [9.1.](9_machine_learning/1_basics_of_mlp/tutorial.ipynb) | [9.3.](9_machine_learning/3_advanced_ann/tutorial.ipynb)
    - `error` [9.1.](9_machine_learning/1_basics_of_mlp/tutorial.ipynb)

- `liblibra::libcontrol_parameters::Control_Parameters` [5.1.1.](5_electronic_structure/1_eht/1_compact/tutorial.ipynb)

- `liblibra::libconverters`
  - `StringList` [10.1.](10_auxiliary_functions/1_util_functions/tutorial.ipynb)
  - `StringMap` [10.1.](10_auxiliary_functions/1_util_functions/tutorial.ipynb)
  - `StringDoubleMap` [10.1.](10_auxiliary_functions/1_util_functions/tutorial.ipynb)
  - `StringIntMap` [10.1.](10_auxiliary_functions/1_util_functions/tutorial.ipynb)
  - `StringVDoubleMap` [10.1.](10_auxiliary_functions/1_util_functions/tutorial.ipynb)

- `liblibra::libchemobjects`
  - `libchemsys::System` [12.2.1.](12_molecular_builders/2_chemobjects/1_basic_construction_and_manipulation/tutorial.ipynb)
    - `Atoms` [12.2.1.](12_molecular_builders/2_chemobjects/1_basic_construction_and_manipulation/tutorial.ipynb) | 
              [12.2.2.](12_molecular_builders/2_chemobjects/2_extended_rotation_and_translation/tutorial.ipynb)
    - `CREATE_ATOM` [12.2.1.](12_molecular_builders/2_chemobjects/1_basic_construction_and_manipulation/tutorial.ipynb) |
                    [13.3.](13_force_fields_and_classical_md/3_mm_optimization/tutorial.ipynb)
    - `determine_functional_groups` [12.2.1.](12_molecular_builders/2_chemobjects/1_basic_construction_and_manipulation/tutorial.ipynb) | 
                                    [12.2.2.](12_molecular_builders/2_chemobjects/2_extended_rotation_and_translation/tutorial.ipynb)
    - `Fragments` [12.2.1.](12_molecular_builders/2_chemobjects/1_basic_construction_and_manipulation/tutorial.ipynb) | 
                  [12.2.2.](12_molecular_builders/2_chemobjects/2_extended_rotation_and_translation/tutorial.ipynb)
    - `GROUP_ATOMS` [12.2.1.](12_molecular_builders/2_chemobjects/1_basic_construction_and_manipulation/tutorial.ipynb) |
                    [12.2.2.](12_molecular_builders/2_chemobjects/2_extended_rotation_and_translation/tutorial.ipynb)
    - `get_xyz` [5.1.1.](5_electronic_structure/1_eht/1_compact/tutorial.ipynb) 
                [12.1.](12_molecular_builders/1_crystal_and_qd_builder/tutorial.ipynb)
    - `init_box` [12.1.](12_molecular_builders/1_crystal_and_qd_builder/tutorial.ipynb) | 
                 [12.2.1.](12_molecular_builders/2_chemobjects/1_basic_construction_and_manipulation/tutorial.ipynb)
    - `init_atom_velocities` [13.2.](13_force_fields_and_classical_md/2_atomistic_Hamiltonian/tutorial.ipynb)
    - `init_fragments` [12.2.1.](12_molecular_builders/2_chemobjects/1_basic_construction_and_manipulation/tutorial.ipynb) |
                       [12.2.2.](12_molecular_builders/2_chemobjects/2_extended_rotation_and_translation/tutorial.ipynb)
    - `LINK_ATOMS` [12.2.1.](12_molecular_builders/2_chemobjects/1_basic_construction_and_manipulation/tutorial.ipynb) |
                   [13.3.](13_force_fields_and_classical_md/3_mm_optimization/tutorial.ipynb)
    - `Number_of_atoms` [12.2.1.](12_molecular_builders/2_chemobjects/1_basic_construction_and_manipulation/tutorial.ipynb) | 
                        [12.2.2.](12_molecular_builders/2_chemobjects/2_extended_rotation_and_translation/tutorial.ipynb) |
                        [5.1.1.](5_electronic_structure/1_eht/1_compact/tutorial.ipynb)
    - `Number_of_angles` [12.2.1.](12_molecular_builders/2_chemobjects/1_basic_construction_and_manipulation/tutorial.ipynb) | 
                         [12.2.2.](12_molecular_builders/2_chemobjects/2_extended_rotation_and_translation/tutorial.ipynb)
    - `Number_of_bonds` [12.2.1.](12_molecular_builders/2_chemobjects/1_basic_construction_and_manipulation/tutorial.ipynb) | 
                        [12.2.2.](12_molecular_builders/2_chemobjects/2_extended_rotation_and_translation/tutorial.ipynb)
    - `Number_of_dihedrals` [12.2.1.](12_molecular_builders/2_chemobjects/1_basic_construction_and_manipulation/tutorial.ipynb) | 
                            [12.2.2.](12_molecular_builders/2_chemobjects/2_extended_rotation_and_translation/tutorial.ipynb)
    - `Number_of_fragments` [12.2.1.](12_molecular_builders/2_chemobjects/1_basic_construction_and_manipulation/tutorial.ipynb) | 
                            [12.2.2.](12_molecular_builders/2_chemobjects/2_extended_rotation_and_translation/tutorial.ipynb)
    - `Number_of_impropers` [12.2.1.](12_molecular_builders/2_chemobjects/1_basic_construction_and_manipulation/tutorial.ipynb) | 
                            [12.2.2.](12_molecular_builders/2_chemobjects/2_extended_rotation_and_translation/tutorial.ipynb)
    - `print_ent` [12.1.](12_molecular_builders/1_crystal_and_qd_builder/tutorial.ipynb) | 
                  [12.2.1.](12_molecular_builders/2_chemobjects/1_basic_construction_and_manipulation/tutorial.ipynb)
    - `print_xyz` [12.2.1.](12_molecular_builders/2_chemobjects/1_basic_construction_and_manipulation/tutorial.ipynb)
    - `ROTATE_FRAGMENT` [12.2.1.](12_molecular_builders/2_chemobjects/1_basic_construction_and_manipulation/tutorial.ipynb) |
                        [12.2.2.](12_molecular_builders/2_chemobjects/2_extended_rotation_and_translation/tutorial.ipynb)
    - `set_atomic_q` [13.2.](13_force_fields_and_classical_md/2_atomistic_Hamiltonian/tutorial.ipynb)
    - `show_atoms` [12.2.1.](12_molecular_builders/2_chemobjects/1_basic_construction_and_manipulation/tutorial.ipynb)
    - `show_bonds` [12.2.1.](12_molecular_builders/2_chemobjects/1_basic_construction_and_manipulation/tutorial.ipynb)
    - `show_fragments` [12.2.1.](12_molecular_builders/2_chemobjects/1_basic_construction_and_manipulation/tutorial.ipynb)
    - `show_molecules` [12.2.1.](12_molecular_builders/2_chemobjects/1_basic_construction_and_manipulation/tutorial.ipynb)
    - `show_rings` [12.2.1.](12_molecular_builders/2_chemobjects/1_basic_construction_and_manipulation/tutorial.ipynb)
    - `System` [12.1.](12_molecular_builders/1_crystal_and_qd_builder/tutorial.ipynb) | [12.2.1.](12_molecular_builders/2_chemobjects/1_basic_construction_and_manipulation/tutorial.ipynb)
    - `TRANSLATE_FRAGMENT` [12.2.1.](12_molecular_builders/2_chemobjects/1_basic_construction_and_manipulation/tutorial.ipynb)
  - `libmol`
    - `Atom` [12.2.1.](12_molecular_builders/2_chemobjects/1_basic_construction_and_manipulation/tutorial.ipynb)
      - `Atom` [12.2.1.](12_molecular_builders/2_chemobjects/1_basic_construction_and_manipulation/tutorial.ipynb)
      - `Atom_id` [12.2.1.](12_molecular_builders/2_chemobjects/1_basic_construction_and_manipulation/tutorial.ipynb)
      - `Atom_RB` [12.2.1.](12_molecular_builders/2_chemobjects/1_basic_construction_and_manipulation/tutorial.ipynb)
      - `globAtom_Index` [12.2.1.](12_molecular_builders/2_chemobjects/1_basic_construction_and_manipulation/tutorial.ipynb)
      - `save` [12.2.1.](12_molecular_builders/2_chemobjects/1_basic_construction_and_manipulation/tutorial.ipynb)
      - `show_info`[12.2.1.](12_molecular_builders/2_chemobjects/1_basic_construction_and_manipulation/tutorial.ipynb)
    - `AtomList` [10.1.](10_auxiliary_functions/1_util_functions/tutorial.ipynb)
    - `GroupList` [10.1.](10_auxiliary_functions/1_util_functions/tutorial.ipynb)
    - `MoleculeList` [10.1.](10_auxiliary_functions/1_util_functions/tutorial.ipynb)
  - `libuniverse::Universe` [5.1.1.](5_electronic_structure/1_eht/1_compact/tutorial.ipynb) | 
                            [12.2.1.](12_molecular_builders/2_chemobjects/1_basic_construction_and_manipulation/tutorial.ipynb) |
                            [12.2.2.](12_molecular_builders/2_chemobjects/2_extended_rotation_and_translation/tutorial.ipynb)  

- `liblibra::libdata`
  - `DATA` [7.3.](7_special_functions/3_data_statistics/tutorial.ipynb) | [7.4.2.](7_special_functions/4_random_numbers/2_metropolis/tutorial.ipynb)
    - `Data` [7.3.](7_special_functions/3_data_statistics/tutorial.ipynb)
    - `ave` [7.3.](7_special_functions/3_data_statistics/tutorial.ipynb)
    - `var` [7.3.](7_special_functions/3_data_statistics/tutorial.ipynb)
    - `sd` [7.3.](7_special_functions/3_data_statistics/tutorial.ipynb)
    - `se` [7.3.](7_special_functions/3_data_statistics/tutorial.ipynb)
    - `mse` [7.3.](7_special_functions/3_data_statistics/tutorial.ipynb)
    - `mae` [7.3.](7_special_functions/3_data_statistics/tutorial.ipynb)
    - `rmse` [7.3.](7_special_functions/3_data_statistics/tutorial.ipynb)
    - `min_val` [7.3.](7_special_functions/3_data_statistics/tutorial.ipynb)
    - `min_indx` [7.3.](7_special_functions/3_data_statistics/tutorial.ipynb)
    - `max_val` [7.3.](7_special_functions/3_data_statistics/tutorial.ipynb)
    - `max_indx` [7.3.](7_special_functions/3_data_statistics/tutorial.ipynb)
    - `scale_factor` [7.3.](7_special_functions/3_data_statistics/tutorial.ipynb)
    - `shift_amount` [7.3.](7_special_functions/3_data_statistics/tutorial.ipynb)
    - `LinearTransformData` [7.3.](7_special_functions/3_data_statistics/tutorial.ipynb)
    - `invLinearTransformData` [7.3.](7_special_functions/3_data_statistics/tutorial.ipynb)
    - `ScaleData` [7.3.](7_special_functions/3_data_statistics/tutorial.ipynb)
    - `ShiftData` [7.3.](7_special_functions/3_data_statistics/tutorial.ipynb)
    - `NormalizeData` [7.3.](7_special_functions/3_data_statistics/tutorial.ipynb)
    - `Calculate_Estimators` [7.3.](7_special_functions/3_data_statistics/tutorial.ipynb) |
                             [11.2.2.](11_program_specific_methods/2_qe_methods/2_md/1_co2/tutorial.ipynb)
    - `Calculate_MiniMax` [7.3.](7_special_functions/3_data_statistics/tutorial.ipynb) |
                          [11.2.2.](11_program_specific_methods/2_qe_methods/2_md/1_co2/tutorial.ipynb)
    - `Calculate_Distribution` [7.3.](7_special_functions/3_data_statistics/tutorial.ipynb) |
                               [7.4.1.](7_special_functions/4_random_numbers/1_basics/tutorial.ipynb) |
                               [7.4.2.](7_special_functions/4_random_numbers/2_metropolis/tutorial.ipynb) |
                               [11.2.2.](11_program_specific_methods/2_qe_methods/2_md/1_co2/tutorial.ipynb)
  - `DATAList` [10.1.](10_auxiliary_functions/1_util_functions/tutorial.ipynb)

- `liblibra::libdyn`
  - `libelectronic`
    - `Electronic`
      - `Electronic` [13.2.](13_force_fields_and_classical_md/2_atomistic_Hamiltonian/tutorial.ipynb)
    - `ElectronicList` [10.1.](10_auxiliary_functions/1_util_functions/tutorial.ipynb)
  - `libnuclear`
    - `Nuclear`
      - `q` [13.2.](13_force_fields_and_classical_md/2_atomistic_Hamiltonian/tutorial.ipynb)
      - `Nuclear` [13.2.](13_force_fields_and_classical_md/2_atomistic_Hamiltonian/tutorial.ipynb)
    - `NuclearList` [10.1.](10_auxiliary_functions/1_util_functions/tutorial.ipynb)
  - `libthermostat`
    - `ThermostatList` [10.1.](10_auxiliary_functions/1_util_functions/tutorial.ipynb)

- `liblibra::libforcefield`
  - `Angle_Record`
    - `Angle_Record` [13.1.](13_force_fields_and_classical_md/1_force_field_basics/tutorial.ipynb) |
                     [13.2.](13_force_fields_and_classical_md/2_atomistic_Hamiltonian/tutorial.ipynb)
    - `Atom1_ff_type` [13.1.](13_force_fields_and_classical_md/1_force_field_basics/tutorial.ipynb) |
                      [13.2.](13_force_fields_and_classical_md/2_atomistic_Hamiltonian/tutorial.ipynb)
    - `Atom2_ff_type` [13.1.](13_force_fields_and_classical_md/1_force_field_basics/tutorial.ipynb) | 
                      [13.2.](13_force_fields_and_classical_md/2_atomistic_Hamiltonian/tutorial.ipynb)
    - `Atom3_ff_type` [13.1.](13_force_fields_and_classical_md/1_force_field_basics/tutorial.ipynb) |
                      [13.2.](13_force_fields_and_classical_md/2_atomistic_Hamiltonian/tutorial.ipynb)
    - `Angle_k_theta` [13.1.](13_force_fields_and_classical_md/1_force_field_basics/tutorial.ipynb) |
                      [13.2.](13_force_fields_and_classical_md/2_atomistic_Hamiltonian/tutorial.ipynb)
    - `Angle_theta_eq` [13.1.](13_force_fields_and_classical_md/1_force_field_basics/tutorial.ipynb) |
                       [13.2.](13_force_fields_and_classical_md/2_atomistic_Hamiltonian/tutorial.ipynb)
    - `set` [13.1.](13_force_fields_and_classical_md/1_force_field_basics/tutorial.ipynb) |
            [13.2.](13_force_fields_and_classical_md/2_atomistic_Hamiltonian/tutorial.ipynb)
    - `show_info` [13.1.](13_force_fields_and_classical_md/1_force_field_basics/tutorial.ipynb) |
                  [13.2.](13_force_fields_and_classical_md/2_atomistic_Hamiltonian/tutorial.ipynb)
  - `Angle_RecordList` [10.1.](10_auxiliary_functions/1_util_functions/tutorial.ipynb)
  - `Atom_Record`
    - `Atom_Record` [13.1.](13_force_fields_and_classical_md/1_force_field_basics/tutorial.ipynb) |
                    [13.2.](13_force_fields_and_classical_md/2_atomistic_Hamiltonian/tutorial.ipynb)
    - `Atom_ff_int_type` [13.1.](13_force_fields_and_classical_md/1_force_field_basics/tutorial.ipynb) |
                         [13.2.](13_force_fields_and_classical_md/2_atomistic_Hamiltonian/tutorial.ipynb)
    - `Atom_ff_type` [13.1.](13_force_fields_and_classical_md/1_force_field_basics/tutorial.ipynb) |
                     [13.2.](13_force_fields_and_classical_md/2_atomistic_Hamiltonian/tutorial.ipynb)
    - `set` [13.1.](13_force_fields_and_classical_md/1_force_field_basics/tutorial.ipynb) |
            [13.2.](13_force_fields_and_classical_md/2_atomistic_Hamiltonian/tutorial.ipynb)
    - `show_info` [13.1.](13_force_fields_and_classical_md/1_force_field_basics/tutorial.ipynb) |
                  [13.2.](13_force_fields_and_classical_md/2_atomistic_Hamiltonian/tutorial.ipynb)
  - `Bond_RecordList` [10.1.](10_auxiliary_functions/1_util_functions/tutorial.ipynb)
  - `Dihedral_RecordList` [10.1.](10_auxiliary_functions/1_util_functions/tutorial.ipynb)
  - `ForceField`
    - `Add_Angle_Record` [13.1.](13_force_fields_and_classical_md/1_force_field_basics/tutorial.ipynb) |
                         [13.2.](13_force_fields_and_classical_md/2_atomistic_Hamiltonian/tutorial.ipynb)
    - `Add_Atom_Record` [13.1.](13_force_fields_and_classical_md/1_force_field_basics/tutorial.ipynb) |
                        [13.2.](13_force_fields_and_classical_md/2_atomistic_Hamiltonian/tutorial.ipynb)
    - `ForceField` [13.1.](13_force_fields_and_classical_md/1_force_field_basics/tutorial.ipynb) |
                   [13.2.](13_force_fields_and_classical_md/2_atomistic_Hamiltonian/tutorial.ipynb)
    - `bond_functional` [13.1.](13_force_fields_and_classical_md/1_force_field_basics/tutorial.ipynb)
    - `angle_functional` [13.1.](13_force_fields_and_classical_md/1_force_field_basics/tutorial.ipynb)
    - `dihedral_functional` [13.1.](13_force_fields_and_classical_md/1_force_field_basics/tutorial.ipynb)
    - `oop_functional` [13.1.](13_force_fields_and_classical_md/1_force_field_basics/tutorial.ipynb)
    - `vdw_functional` [13.1.](13_force_fields_and_classical_md/1_force_field_basics/tutorial.ipynb)
    - `elec_functional` [13.1.](13_force_fields_and_classical_md/1_force_field_basics/tutorial.ipynb)
    - `mb_functional` [13.1.](13_force_fields_and_classical_md/1_force_field_basics/tutorial.ipynb)
    - `cg_functional` [13.1.](13_force_fields_and_classical_md/1_force_field_basics/tutorial.ipynb)
    - `mb_excl_functional` [13.1.](13_force_fields_and_classical_md/1_force_field_basics/tutorial.ipynb)
    - `set_functionals` [13.1.](13_force_fields_and_classical_md/1_force_field_basics/tutorial.ipynb)
    - `show_angle_records` [13.1.](13_force_fields_and_classical_md/1_force_field_basics/tutorial.ipynb)
    - `show_atom_records` [13.1.](13_force_fields_and_classical_md/1_force_field_basics/tutorial.ipynb)
    - `show_info` [13.1.](13_force_fields_and_classical_md/1_force_field_basics/tutorial.ipynb)
  - `Fragment_RecordList` [10.1.](10_auxiliary_functions/1_util_functions/tutorial.ipynb)

- `liblibra::libhamiltonian
  - `libhamiltonian_atomistic`
    - `libhamiltonian_qm`
      - `listHamiltonian_QM`
        - `compute_scf` [5.1.1.](5_electronic_structure/1_eht/1_compact/tutorial.ipynb)
        - `get_electronic_structure` [5.1.1.](5_electronic_structure/1_eht/1_compact/tutorial.ipynb)
        - `basis_ao` [5.1.1.](5_electronic_structure/1_eht/1_compact/tutorial.ipynb)
        - `atom_to_ao_map` [5.1.1.](5_electronic_structure/1_eht/1_compact/tutorial.ipynb)
      - `listHamiltonian_QMList` [10.1.](10_auxiliary_functions/1_util_functions/tutorial.ipynb)
      - `listHamiltonian_QMMap` [10.1.](10_auxiliary_functions/1_util_functions/tutorial.ipynb)
    - `Hamiltonian_Atomistic`
      - `compute` [13.1.](13_force_fields_and_classical_md/1_force_field_basics/tutorial.ipynb)
      - `Hamiltonian_Atomistic` [13.1.](13_force_fields_and_classical_md/1_force_field_basics/tutorial.ipynb)
      - `set_Hamiltonian_type` [13.1.](13_force_fields_and_classical_md/1_force_field_basics/tutorial.ipynb)
      - `set_interactions_for_atoms` [13.1.](13_force_fields_and_classical_md/1_force_field_basics/tutorial.ipynb)
      - `set_system` [13.1.](13_force_fields_and_classical_md/1_force_field_basics/tutorial.ipynb)
      - `show_interactions` [13.1.](13_force_fields_and_classical_md/1_force_field_basics/tutorial.ipynb)
      - `show_interactions_statistics` [13.1.](13_force_fields_and_classical_md/1_force_field_basics/tutorial.ipynb)
    - `Hamiltonian_AtomisticList` [10.1.](10_auxiliary_functions/1_util_functions/tutorial.ipynb)
    - `libhamiltonian_mm`
      - `Hamiltonian_MM`
        - `Hamiltonian_MM` [13.1.](13_force_fields_and_classical_md/1_force_field_basics/tutorial.ipynb)
      - `listHamiltonian_MM`
        - `active_interactions` [13.1.](13_force_fields_and_classical_md/1_force_field_basics/tutorial.ipynb)
        - `interactions` [13.1.](13_force_fields_and_classical_md/1_force_field_basics/tutorial.ipynb)
        - `is_active` [13.1.](13_force_fields_and_classical_md/1_force_field_basics/tutorial.ipynb)
        - `is_new_interaction` [13.1.](13_force_fields_and_classical_md/1_force_field_basics/tutorial.ipynb)
        - `listHamiltonian_MM` [13.1.](13_force_fields_and_classical_md/1_force_field_basics/tutorial.ipynb)
  - `libhamiltonian_extern`
    - `Hamiltonian_ExternList` [10.1.](10_auxiliary_functions/1_util_functions/tutorial.ipynb)
  - `libhamiltonian_generic`
    - `Hamiltonian` [13.1.](13_force_fields_and_classical_md/1_force_field_basics/tutorial.ipynb)
      - `compute` [13.1.](13_force_fields_and_classical_md/1_force_field_basics/tutorial.ipynb)
      - `H` [13.1.](13_force_fields_and_classical_md/1_force_field_basics/tutorial.ipynb)
      - `dHdq` [13.1.](13_force_fields_and_classical_md/1_force_field_basics/tutorial.ipynb)
    - `HamiltonianList` [10.1.](10_auxiliary_functions/1_util_functions/tutorial.ipynb)
    - `nHamiltonianList` [10.1.](10_auxiliary_functions/1_util_functions/tutorial.ipynb)
  -`libhamiltonian_model`
    - `Hamiltonian_ModelList` [10.1.](10_auxiliary_functions/1_util_functions/tutorial.ipynb)

  - `Electronic_Structure`
    - `Nelec` [5.1.1.](5_electronic_structure/1_eht/1_compact/tutorial.ipynb)
    - `Norb` [5.1.1.](5_electronic_structure/1_eht/1_compact/tutorial.ipynb)
    - `get_bands_alp` [5.1.1.](5_electronic_structure/1_eht/1_compact/tutorial.ipynb)
    - `get_bands_bet` [5.1.1.](5_electronic_structure/1_eht/1_compact/tutorial.ipynb)
    - `get_occ_alp` [5.1.1.](5_electronic_structure/1_eht/1_compact/tutorial.ipynb)
    - `get_occ_bet` [5.1.1.](5_electronic_structure/1_eht/1_compact/tutorial.ipynb)

- `liblibra::libqobjects`
  - `PromitiveGList`  [10.1.](10_auxiliary_functions/1_util_functions/tutorial.ipynb)
  - `AOList` [10.1.](10_auxiliary_functions/1_util_functions/tutorial.ipynb)
  - `SDList` [10.1.](10_auxiliary_functions/1_util_functions/tutorial.ipynb)
  - `PWList` [10.1.](10_auxiliary_functions/1_util_functions/tutorial.ipynb)

- `liblibra::librandom`
  - `Random`
    - `Random` [7.4.1.](7_special_functions/4_random_numbers/1_basics/tutorial.ipynb) | 
               [7.4.2.](7_special_functions/4_random_numbers/2_metropolis/tutorial.ipynb)
    - `uniform` [7.4.1.](7_special_functions/4_random_numbers/1_basics/tutorial.ipynb) |
                [7.3.](7_special_functions/3_data_statistics/tutorial.ipynb) | 
                [7.4.2.](7_special_functions/4_random_numbers/2_metropolis/tutorial.ipynb)
    - `p_uniform` [7.4.1.](7_special_functions/4_random_numbers/1_basics/tutorial.ipynb)
    - `normal` [7.4.1.](7_special_functions/4_random_numbers/1_basics/tutorial.ipynb) | 
               [7.2.](7_special_functions/2_gaussian_kernel_algorithm/tutorial.ipynb) | 
               [7.3.](7_special_functions/3_data_statistics/tutorial.ipynb) |
               [9.1.](9_machine_learning/1_basics_of_mlp/tutorial.ipynb) | 
               [7.4.2.](7_special_functions/4_random_numbers/2_metropolis/tutorial.ipynb)
    - `p_normal` [7.4.1.](7_special_functions/4_random_numbers/1_basics/tutorial.ipynb)
    - `exponential` [7.4.1.](7_special_functions/4_random_numbers/1_basics/tutorial.ipynb)
    - `exponential` [7.4.1.](7_special_functions/4_random_numbers/1_basics/tutorial.ipynb)
    - `poiss1` [7.4.1.](7_special_functions/4_random_numbers/1_basics/tutorial.ipynb)
    - `poiss2` [7.4.1.](7_special_functions/4_random_numbers/1_basics/tutorial.ipynb)
    - `p_poiss` [7.4.1.](7_special_functions/4_random_numbers/1_basics/tutorial.ipynb)
    - `gamma` [7.4.1.](7_special_functions/4_random_numbers/1_basics/tutorial.ipynb)
    - `p_gamma` [7.4.1.](7_special_functions/4_random_numbers/1_basics/tutorial.ipynb)

- `liblibra::liblinalg`
  - `CMATRIX`
    - `real` [11.1.1](11_program_specific_methods/1_ergoscf_methods/1_basics/tutorial.ipynb)
    - `H` [11.1.1](11_program_specific_methods/1_ergoscf_methods/1_basics/tutorial.ipynb)
    - `show_matrix` [11.1.1](11_program_specific_methods/1_ergoscf_methods/1_basics/tutorial.ipynb)
  - `intList` [10.1.](10_auxiliary_functions/1_util_functions/tutorial.ipynb)
  - `floatList` [10.1.](10_auxiliary_functions/1_util_functions/tutorial.ipynb)
  - `doubleList` [10.1.](10_auxiliary_functions/1_util_functions/tutorial.ipynb)
  - `complexList` [10.1.](10_auxiliary_functions/1_util_functions/tutorial.ipynb)
  - `intList2` [10.1.](10_auxiliary_functions/1_util_functions/tutorial.ipynb)
  - `floatList2` [10.1.](10_auxiliary_functions/1_util_functions/tutorial.ipynb)
  - `doubleList2` [10.1.](10_auxiliary_functions/1_util_functions/tutorial.ipynb)
  - `complexList2` [10.1.](10_auxiliary_functions/1_util_functions/tutorial.ipynb)
  - `intList3` [10.1.](10_auxiliary_functions/1_util_functions/tutorial.ipynb)
  - `floatList3` [10.1.](10_auxiliary_functions/1_util_functions/tutorial.ipynb)
  - `doubleList3` [10.1.](10_auxiliary_functions/1_util_functions/tutorial.ipynb)
  - `complexList3` [10.1.](10_auxiliary_functions/1_util_functions/tutorial.ipynb)
  - `intMap` [10.1.](10_auxiliary_functions/1_util_functions/tutorial.ipynb)
  - `floatMap` [10.1.](10_auxiliary_functions/1_util_functions/tutorial.ipynb)
  - `doubleMap` [10.1.](10_auxiliary_functions/1_util_functions/tutorial.ipynb)
  - `complexMap` [10.1.](10_auxiliary_functions/1_util_functions/tutorial.ipynb)
  - `MATRIXList` [10.1.](10_auxiliary_functions/1_util_functions/tutorial.ipynb)
  - `MATRIXMap` [10.1.](10_auxiliary_functions/1_util_functions/tutorial.ipynb)
  - `CMATRIXList` [10.1.](10_auxiliary_functions/1_util_functions/tutorial.ipynb)
  - `CMATRIXMap` [10.1.](10_auxiliary_functions/1_util_functions/tutorial.ipynb)
  - `MATRIX3x3List` [10.1.](10_auxiliary_functions/1_util_functions/tutorial.ipynb)
  - `MATRIX3x3Map` [10.1.](10_auxiliary_functions/1_util_functions/tutorial.ipynb)
  - `QUATERNIONList` [10.1.](10_auxiliary_functions/1_util_functions/tutorial.ipynb)
  - `QUATERNIONMap` [10.1.](10_auxiliary_functions/1_util_functions/tutorial.ipynb)
  - `VECTORList` [10.1.](10_auxiliary_functions/1_util_functions/tutorial.ipynb)
  - `VECTORMap` [10.1.](10_auxiliary_functions/1_util_functions/tutorial.ipynb)

- `libra_py`
  - `data_savers`
    - `hdf5_saver`
      - `set_compression_level` [8.1.](8_model_hamiltonians/1_pes_plotting/tutorial.ipynb)
      - `add_dataset` [8.1.](8_model_hamiltonians/1_pes_plotting/tutorial.ipynb)
      - `save_matrix` [8.1.](8_model_hamiltonians/1_pes_plotting/tutorial.ipynb)
      - `hdf5_saver` [8.1.](8_model_hamiltonians/1_pes_plotting/tutorial.ipynb)

- `liblibra::libdyn::libwfcgrid2`
  - `Wfcgrid2` [6.4.2.](6_dynamics/4_wavepackets/2_dvr_basics/tutorial.ipynb)
    - `nstates` [6.4.2.](6_dynamics/4_wavepackets/2_dvr_basics/tutorial.ipynb)
    - `ndof` [6.4.2.](6_dynamics/4_wavepackets/2_dvr_basics/tutorial.ipynb)
    - `Npts` [6.4.2.](6_dynamics/4_wavepackets/2_dvr_basics/tutorial.ipynb)
    - `npts` [6.4.2.](6_dynamics/4_wavepackets/2_dvr_basics/tutorial.ipynb)
    - `rmin` [6.4.2.](6_dynamics/4_wavepackets/2_dvr_basics/tutorial.ipynb)
    - `rmax` [6.4.2.](6_dynamics/4_wavepackets/2_dvr_basics/tutorial.ipynb)
    - `dr` [6.4.2.](6_dynamics/4_wavepackets/2_dvr_basics/tutorial.ipynb)
    - `kmin` [6.4.2.](6_dynamics/4_wavepackets/2_dvr_basics/tutorial.ipynb)
    - `dk` [6.4.2.](6_dynamics/4_wavepackets/2_dvr_basics/tutorial.ipynb)
    - `gmap` [6.4.2.](6_dynamics/4_wavepackets/2_dvr_basics/tutorial.ipynb)
    - `imap` [6.4.2.](6_dynamics/4_wavepackets/2_dvr_basics/tutorial.ipynb)
    - `PSI_dia` [6.4.2.](6_dynamics/4_wavepackets/2_dvr_basics/tutorial.ipynb)
    - `reciPSI_dia` [6.4.2.](6_dynamics/4_wavepackets/2_dvr_basics/tutorial.ipynb)
    - `PSI_adi` [6.4.2.](6_dynamics/4_wavepackets/2_dvr_basics/tutorial.ipynb)
    - `reciPSI_adi` [6.4.2.](6_dynamics/4_wavepackets/2_dvr_basics/tutorial.ipynb)
    - `Hdia` [6.4.2.](6_dynamics/4_wavepackets/2_dvr_basics/tutorial.ipynb)
    - `U` [6.4.2.](6_dynamics/4_wavepackets/2_dvr_basics/tutorial.ipynb)
    - `add_wfc_Gau` [6.4.2.](6_dynamics/4_wavepackets/2_dvr_basics/tutorial.ipynb)
    - `add_wfc_HO` [6.4.2.](6_dynamics/4_wavepackets/2_dvr_basics/tutorial.ipynb)
    - `add_wfc_ARB` [6.4.2.](6_dynamics/4_wavepackets/2_dvr_basics/tutorial.ipynb)
    - `norm` [6.4.2.](6_dynamics/4_wavepackets/2_dvr_basics/tutorial.ipynb)
    - `e_kin` [6.4.2.](6_dynamics/4_wavepackets/2_dvr_basics/tutorial.ipynb)
    - `e_pot` [6.4.2.](6_dynamics/4_wavepackets/2_dvr_basics/tutorial.ipynb)
    - `e_tot` [6.4.2.](6_dynamics/4_wavepackets/2_dvr_basics/tutorial.ipynb)
    - `get_pow_q` [6.4.2.](6_dynamics/4_wavepackets/2_dvr_basics/tutorial.ipynb)
    - `get_pow_p` [6.4.2.](6_dynamics/4_wavepackets/2_dvr_basics/tutorial.ipynb)
    - `get_den_mat` [6.4.2.](6_dynamics/4_wavepackets/2_dvr_basics/tutorial.ipynb)
    - `get_pops` [6.4.2.](6_dynamics/4_wavepackets/2_dvr_basics/tutorial.ipynb) | [6.4.3.](6_dynamics/4_wavepackets/3_soft_propagation/tutorial.ipynb)
    - `update_propagator_H` [6.4.2.](6_dynamics/4_wavepackets/2_dvr_basics/tutorial.ipynb)
    - `update_propagator_K` [6.4.2.](6_dynamics/4_wavepackets/2_dvr_basics/tutorial.ipynb)
    - `SOFT_propagate` [6.4.2.](6_dynamics/4_wavepackets/2_dvr_basics/tutorial.ipynb)
    - `update_real` [6.4.3.](6_dynamics/4_wavepackets/3_soft_propagation/tutorial.ipynb)
    - `update_reciprocal` [6.4.2.](6_dynamics/4_wavepackets/2_dvr_basics/tutorial.ipynb)
    - `normalize` [6.4.2.](6_dynamics/4_wavepackets/2_dvr_basics/tutorial.ipynb)
    - `update_Hamiltonian` [6.4.2.](6_dynamics/4_wavepackets/2_dvr_basics/tutorial.ipynb)
    - `update_adiabatic` [6.4.2.](6_dynamics/4_wavepackets/2_dvr_basics/tutorial.ipynb)
    - `update_diabatic` [6.4.3.](6_dynamics/4_wavepackets/3_soft_propagation/tutorial.ipynb)
    - `print_wfc_1D` [6.4.3.](6_dynamics/4_wavepackets/3_soft_propagation/tutorial.ipynb)
    - `print_reci_wfc_1D` [6.4.3.](6_dynamics/4_wavepackets/3_soft_propagation/tutorial.ipynb)
    - `print_wfc_2D` [6.4.3.](6_dynamics/4_wavepackets/3_soft_propagation/tutorial.ipynb)
    - `print_reci_wfc_2D` [6.4.3.](6_dynamics/4_wavepackets/3_soft_propagation/tutorial.ipynb)

    
