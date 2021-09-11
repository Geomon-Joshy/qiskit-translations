ZZFeatureMap
============

.. currentmodule:: qiskit.circuit.library

.. autoclass:: ZZFeatureMap
   :no-members:
   :show-inheritance:

   .. rubric:: Methods

   .. autosummary::
      :nosignatures:
      :toctree: ../stubs/

      ~ZZFeatureMap.add_bits
      ~ZZFeatureMap.add_calibration
      ~ZZFeatureMap.add_layer
      ~ZZFeatureMap.add_register
      ~ZZFeatureMap.append
      ~ZZFeatureMap.assign_parameters
      ~ZZFeatureMap.barrier
      ~ZZFeatureMap.bind_parameters
      ~ZZFeatureMap.cast
      ~ZZFeatureMap.cbit_argument_conversion
      ~ZZFeatureMap.ccx
      ~ZZFeatureMap.ch
      ~ZZFeatureMap.cls_instances
      ~ZZFeatureMap.cls_prefix
      ~ZZFeatureMap.cnot
      ~ZZFeatureMap.combine
      ~ZZFeatureMap.compose
      ~ZZFeatureMap.control
      ~ZZFeatureMap.copy
      ~ZZFeatureMap.count_ops
      ~ZZFeatureMap.cp
      ~ZZFeatureMap.crx
      ~ZZFeatureMap.cry
      ~ZZFeatureMap.crz
      ~ZZFeatureMap.cswap
      ~ZZFeatureMap.csx
      ~ZZFeatureMap.cu
      ~ZZFeatureMap.cu1
      ~ZZFeatureMap.cu3
      ~ZZFeatureMap.cx
      ~ZZFeatureMap.cy
      ~ZZFeatureMap.cz
      ~ZZFeatureMap.dcx
      ~ZZFeatureMap.decompose
      ~ZZFeatureMap.delay
      ~ZZFeatureMap.depth
      ~ZZFeatureMap.diagonal
      ~ZZFeatureMap.draw
      ~ZZFeatureMap.ecr
      ~ZZFeatureMap.extend
      ~ZZFeatureMap.fredkin
      ~ZZFeatureMap.from_qasm_file
      ~ZZFeatureMap.from_qasm_str
      ~ZZFeatureMap.get_entangler_map
      ~ZZFeatureMap.get_instructions
      ~ZZFeatureMap.get_unentangled_qubits
      ~ZZFeatureMap.h
      ~ZZFeatureMap.hamiltonian
      ~ZZFeatureMap.has_register
      ~ZZFeatureMap.i
      ~ZZFeatureMap.id
      ~ZZFeatureMap.initialize
      ~ZZFeatureMap.inverse
      ~ZZFeatureMap.iso
      ~ZZFeatureMap.isometry
      ~ZZFeatureMap.iswap
      ~ZZFeatureMap.mcp
      ~ZZFeatureMap.mcrx
      ~ZZFeatureMap.mcry
      ~ZZFeatureMap.mcrz
      ~ZZFeatureMap.mct
      ~ZZFeatureMap.mcu1
      ~ZZFeatureMap.mcx
      ~ZZFeatureMap.measure
      ~ZZFeatureMap.measure_active
      ~ZZFeatureMap.measure_all
      ~ZZFeatureMap.ms
      ~ZZFeatureMap.num_connected_components
      ~ZZFeatureMap.num_nonlocal_gates
      ~ZZFeatureMap.num_tensor_factors
      ~ZZFeatureMap.num_unitary_factors
      ~ZZFeatureMap.p
      ~ZZFeatureMap.pauli
      ~ZZFeatureMap.pauli_block
      ~ZZFeatureMap.pauli_evolution
      ~ZZFeatureMap.power
      ~ZZFeatureMap.print_settings
      ~ZZFeatureMap.qasm
      ~ZZFeatureMap.qbit_argument_conversion
      ~ZZFeatureMap.qubit_duration
      ~ZZFeatureMap.qubit_start_time
      ~ZZFeatureMap.qubit_stop_time
      ~ZZFeatureMap.r
      ~ZZFeatureMap.rcccx
      ~ZZFeatureMap.rccx
      ~ZZFeatureMap.remove_final_measurements
      ~ZZFeatureMap.repeat
      ~ZZFeatureMap.reset
      ~ZZFeatureMap.reverse_bits
      ~ZZFeatureMap.reverse_ops
      ~ZZFeatureMap.rv
      ~ZZFeatureMap.rx
      ~ZZFeatureMap.rxx
      ~ZZFeatureMap.ry
      ~ZZFeatureMap.ryy
      ~ZZFeatureMap.rz
      ~ZZFeatureMap.rzx
      ~ZZFeatureMap.rzz
      ~ZZFeatureMap.s
      ~ZZFeatureMap.save_amplitudes
      ~ZZFeatureMap.save_amplitudes_squared
      ~ZZFeatureMap.save_density_matrix
      ~ZZFeatureMap.save_expectation_value
      ~ZZFeatureMap.save_expectation_value_variance
      ~ZZFeatureMap.save_matrix_product_state
      ~ZZFeatureMap.save_probabilities
      ~ZZFeatureMap.save_probabilities_dict
      ~ZZFeatureMap.save_stabilizer
      ~ZZFeatureMap.save_state
      ~ZZFeatureMap.save_statevector
      ~ZZFeatureMap.save_statevector_dict
      ~ZZFeatureMap.save_superop
      ~ZZFeatureMap.save_unitary
      ~ZZFeatureMap.sdg
      ~ZZFeatureMap.set_density_matrix
      ~ZZFeatureMap.set_matrix_product_state
      ~ZZFeatureMap.set_stabilizer
      ~ZZFeatureMap.set_statevector
      ~ZZFeatureMap.set_superop
      ~ZZFeatureMap.set_unitary
      ~ZZFeatureMap.size
      ~ZZFeatureMap.snapshot
      ~ZZFeatureMap.snapshot_density_matrix
      ~ZZFeatureMap.snapshot_expectation_value
      ~ZZFeatureMap.snapshot_probabilities
      ~ZZFeatureMap.snapshot_stabilizer
      ~ZZFeatureMap.snapshot_statevector
      ~ZZFeatureMap.squ
      ~ZZFeatureMap.swap
      ~ZZFeatureMap.sx
      ~ZZFeatureMap.sxdg
      ~ZZFeatureMap.t
      ~ZZFeatureMap.tdg
      ~ZZFeatureMap.tensor
      ~ZZFeatureMap.to_gate
      ~ZZFeatureMap.to_instruction
      ~ZZFeatureMap.toffoli
      ~ZZFeatureMap.u
      ~ZZFeatureMap.u1
      ~ZZFeatureMap.u2
      ~ZZFeatureMap.u3
      ~ZZFeatureMap.uc
      ~ZZFeatureMap.ucrx
      ~ZZFeatureMap.ucry
      ~ZZFeatureMap.ucrz
      ~ZZFeatureMap.unitary
      ~ZZFeatureMap.width
      ~ZZFeatureMap.x
      ~ZZFeatureMap.y
      ~ZZFeatureMap.z



   .. rubric:: Attributes

   .. autoattribute:: alpha
   .. autoattribute:: ancillas
   .. autoattribute:: calibrations
   .. autoattribute:: clbits
   .. autoattribute:: data
   .. autoattribute:: entanglement
   .. autoattribute:: entanglement_blocks
   .. autoattribute:: extension_lib
   .. autoattribute:: feature_dimension
   .. autoattribute:: global_phase
   .. autoattribute:: header
   .. autoattribute:: initial_state
   .. autoattribute:: insert_barriers
   .. autoattribute:: instances
   .. autoattribute:: metadata
   .. autoattribute:: num_ancillas
   .. autoattribute:: num_clbits
   .. autoattribute:: num_layers
   .. autoattribute:: num_parameters
   .. autoattribute:: num_parameters_settable
   .. autoattribute:: num_qubits
   .. autoattribute:: ordered_parameters
   .. autoattribute:: parameter_bounds
   .. autoattribute:: parameters
   .. autoattribute:: paulis
   .. autoattribute:: preferred_init_points
   .. autoattribute:: prefix
   .. autoattribute:: qregs
   .. autoattribute:: qubits
   .. autoattribute:: reps
   .. autoattribute:: rotation_blocks
