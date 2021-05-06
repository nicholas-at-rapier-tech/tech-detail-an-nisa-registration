# Tables


## Table :: users
> - id              (user_id)
> - username
> - email
> - role
> - create_at
> - create_by
> - update_at
> - update_by


## Table :: patients
> - id              (patient_id)
> - user_id
> - fullname
> - nik
> - bpjs_id
> - insurance_id
> - date_ob
> - place_ob
> - create_at
> - create_by
> - update_at
> - update_by



## Table :: medical_records
> - id
> - medical_record_id
> - patient_id
> - create_at
> - create_by
> - update_at
> - update_by


## Table :: bpjs_vclaim
> - id
> - patient_id
> - claim_date
> - sep_number



## Table :: ms_insurance
> - code
> - name
> - company
> - remark
> - permit
> - establish
> - address
> - phone
> - email
> - create_at
> - create_by
> - update_at
> - update_by

|code|name|company|remark|permit|establish|address|phone|fax|email|
|:---|:---|:---|:---|:---|:---|:---|:---|:---|:---|
|AJR|Jasa Raharja|PT. Jasa Raharja (Persero)|Asuransi Jasa Raharja|Peraturan Pemerintah RI No 39 Tahun 1980|6 November 1980|Jl. HR. Rasuna Said Kav. C-2 Jakarta Selatan 12920|+62-(021)-5203454|+62-(021)-5220284|pusat@jasaraharja.co.id|
|ALZ|Allianz|PT. Asuransi Allianz Life Indonesia|Asuransi Allianz|KEP513/KMK.017/1996|16 Agustus 1996|Allianz Tower Lantai 7 Jl. HR. Rasuna Said Super Blok 2, Kawasan Kuningan Persada, Jakarta Selatan 12980|+62-(021)-29268888|+62-(021)-29269090|contactus@allianz.co.id|
|FWD|FWD|PT. FWD Indonesia|Asuransi FWD|KEP-05/D.05/2013|18 Februari 2013|Cyber 2 Tower 28th Floor Jl. HR Rasuna Said Blok X-5 Jakarta Selatan|+62-(021)-1500393|+62-(021)-29545500|cs.id@fwd.com|


## Table :: ms_registration_type
> - code
> - title
> - remark
> - create_at
> - create_by
> - update_at
> - update_by

|code|title|remark|
|:---|:---|:---|
|MOBI|mobile|mobile registration|
|SITE|on-site|on site registration|
|SELF|self-service|self service registration|
