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

## endpoints :: registration self_service (public)
> - api/registration/self_service/add/data/{nik}{phone_number}
> - api/registration/self_service/add/bpjs/{nik}{phone_number}{bpjs_number}
> - api/registration/self_service/add/medical_record/{nik}{phone_number}{medical_record_id}

## endpoints :: registration on_site (public)
> - api/registration/on_site/add/data/{nik}{phone_number}
> - api/registration/on_site/add/bpjs/{nik}{phone_number}{bpjs_number}
> - api/registration/on_site/add/medical_record/{nik}{phone_number}{medical_record_id}

## endpoints :: registration mobile (public)
> - api/registration/mobile/add/
> - api/registration/mobile/history

## endpoints :: registration management
> - api/registration/list
> - api/registration/edit/{reg_id}
> - api/registration/cancel/{reg_id}
> - api/registration/view/{reg_id}




