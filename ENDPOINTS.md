# endpoints

## endpoints :: token
> - api/token/request
> - api/token/renewal/{token_access}
> - api/token/revoke/{token_access}

## endpoints :: auth (mobile)
> - api/user/signup
> - api/user/signin
> - api/user/detail/{token_session}
> - api/user/signout/{token_session}

## endpoints :: patient {token_session}
> - api/user/patient/list
> - api/user/patient/detail/{patient_id}
> - api/user/patient/medical_record/{patient_id}

## endpoints :: registration (public)
> - api/registration/add/umum/{nik}{phone_number}
> - api/registration/add/bpjs/{nik}{phone_number}{bpjs_number}
> - api/registration/add/medical_record/{nik}{phone_number}{medical_record_id}
> - api/registration/add/medical_record/import_form_patient_medial_record
> - api/registration/list
> - api/registration/list/by/{token_session}
> - api/registration/edit/{reg_id}
> - api/registration/cancel/{reg_id}
> - api/registration/view/{reg_id}


