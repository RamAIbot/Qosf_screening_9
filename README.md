<h2> QOSF Mentorship Program - Bacth 9 </h2>
<h3> Screening Task </h3>

<h4> Task 3 - Zero Noise Extrapolation </h4>

<p>Zero-noise extrapolation (ZNE) is a noise mitigation technique. It works by intentionally scaling the noise of a quantum circuit to then extrapolate the zero-noise limit of an observable of interest. In this task, you will build a simple ZNE function from scratch:</p>

<OL>
<LI>Build a simple noise model with depolarizing noise.</LI>
<LI>Create different circuits to test your noise models and choose the observable to measure.</LI>
<LI>Apply the unitary folding method.</LI>
<LI>Apply the extrapolation method to get the zero-noise limit. Different extrapolation methods achieve different results, such as Linear, polynomial, and exponential.</LI>
<LI>Compare mitigated and unmitigated results.</LI>
<LI>Bonus: Run your ZNE function in real quantum hardware through the IBM Quantum Service.</LI>
<LI>Check the Mitiq documentation for references. You are not allowed to use the functions from Mitiq or any other frameworks where ZNE is already implemented.</LI>
</OL>

<h4>Outline of the notebook</h4>

<UL>
<LI>Section 1 - Building a simple circuit with depolarizing noise (5%) and testing ZNE.</LI>
<LI>Section 2 - Testing out with various extrapolations tecnhiques.</LI>
<LI>Section 3 - Testing the ZNE process for a circuit with huge depolarization error of 50%.</LI>
<LI>Section 4 - Tesing with a circuit of huge depth (depth 5 X gates).</LI>
<LI>Section 5 - Tesing ZNE implementation with multiple qubits (5 qubits GHz state).</LI>
</UL>
