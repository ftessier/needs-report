# `A.14.0` Cone-Beam CT Dosimetry in Radiation Therapy

## Background

Cone-beam computed tomography (CBCT) is a 3D x-ray imaging technique
where a x-rays are used in a wide-beam geometry to image an object with
3D reconstruction. It's a faster acquisition than classic fan-beam
computed tomography (CT) and has a much wider coverage length per scan
making it an ideal choice for imaging radiotherapy (RT) patients before
treatment. The availability of commercial CBCT systems has dramatically
increased and most new clinical linear accelerator purchases include a
CBCT on the same platform as the accelerator.

Many patients are imaged with CBCT systems just before treatment to
align the target structures or to ensure critical normal tissue targets
are properly out of the field. CBCT is typically reserved for more
complicated delivery techniques where planning margins have been
reduced. The frequency of CBCT imaging for RT treatments varies among
clinics, clinicians, treatment modality, and other technologies
available. It is not uncommon for RT patients to be imaged daily before
treatment for several weeks over the course of their treatment regimen.

The dose received by the patient is largely unaccounted for in the
treatment plan (with the exception of megavoltage CBCT in use by some
manufacturers). Most treatment planning systems (TPS) are designed to
calculate doses from megavoltage beams of radiation and are not designed
to predict doses from the x-ray generators used in CBCT. Therefore, the
dose to the patient is estimated based on a number of different methods,
but not necessarily specific to the patient.

The doses from CBCT are low, but not negligible. There are known risks
of secondary cancers from low-doses of radiation to normal tissues and
these need to be considered. There is a need for patient-specific
dosimetry from CBCT to be able to balance the risks of delivering low
doses of radiation with the benefit of being able to align the internal
anatomy of a patient with higher precision before treatment. Physicians
should be equipped with more knowledge of these doses to make more
educated decisions on the frequency in which CBCT should be used.

Patient-specific CBCT dosimetry starts with accurate dosimetry using
dosimeters with known responses on phantoms. Accurate knowledge of the
energy-dependent nature of the dosimeter is critical, since many
dosimeters are sensitive to energy changes in the range of CBCT x-ray
generators. Dosimeters such as TLDs, diodes, ionization chambers,
MOSFETs, OSLDs, and gel dosimeters are options for CBCT dose
verification. Comparisons with calculations should accompany these
measurements and subsequent calculation platforms should be developed to
accurately predict doses to the patient.
