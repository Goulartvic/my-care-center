patients (coleção)
  [patientId] (documento)
    name
    address
    birthday
    phone_number
    family_doctor_contact
    status
    insurance_id (referência para insurances)
    treatment_center
    list_drugs: [drugId, ...]
    list_doctors: [doctorId, ...]
    list_pharmacies: [pharmacyId, ...]
    list_self_reports: [selfReportId, ...]
    list_assessments: [assessmentId, ...]
    list_notes: [noteId, ...]
    list_diagnoses: [diagnosisId, ...]

insurances
  [insuranceId]
    member_number
    plan_number

doctors
  [doctorId]
    name
    list_patients: [patientId, ...]
    list_drugs: [drugId, ...]

drugs
  [drugId]
    name
    list_pharmacies: [pharmacyId, ...]
    list_patients: [patientId, ...]
    list_side_effects: [sideEffectId, ...]
    onboarding_id

pharmacies
  [pharmacyId]
    name
    address

notes
  [noteId]
    notes_information
    patient_id

self_reports
  [selfReportId]
    report_information
    patient_id

diagnoses
  [diagnosisId]
    diagnosis_information
    patient_id

assessments
  [assessmentId]
    question
    patient_id

onboardings
  [onboardingId]
    list_onboarding_questions: [questionId, ...]
    list_patients: [patientId, ...]

side_effects
  [sideEffectId]
    description
