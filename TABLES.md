# Tables


## Table :: users
> - id (user_id)
> - username
> - email
> - phone_number
> - password
> - role
> - create_at
> - create_by
> - update_at
> - update_by


## Table :: patients
> - id (patient_id)
> - user_id
> - fullname
> - gender
> - blood_type
> - religion
> - education (optional)
> - occupation
> - company
> - nip
> - npwp
> - phone_number
> - nik
> - bpjs_id
> - jkn_number
> - insurance_code
> - insurance_number
> - date_ob
> - place_ob
> - address_ktp
> - adresss_now
> - country
> - province
> - city
> - district
> - sub_district
> - rt
> - rw
> - guarantor_name
> - guarantor_connection
> - first_visit
> - create_at
> - create_by
> - update_at
> - update_by

## Table :: patient_medical_records
> - id
> - medical_record_id
> - patient_id
> - create_at
> - create_by
> - update_at
> - update_by


## Table :: patient_bpjs_vclaim
> - id (vclaim_id)
> - patient_id
> - claim_date
> - sep_number
> - sep_date
> - sep_validity
> - recommend_number
> - recommend_policlinic (poli_id)
> - description
> - create_at
> - create_by
> - update_at
> - update_by

## Table :: patient_registration
> - id (registration_id)
> - registration_date
> - patient_id
> - create_at
> - create_by
> - update_at
> - update_by

## Table :: patient_schedule_booked
> - id (booking_id)
> - booking_date
> - registration_id
> - schedule_id
> - description
> - status
> - create_at
> - create_by
> - update_at
> - update_by

## Table :: schedule_quota
> - id (quota_id)
> - schedule_id
> - booking_id
> - patient_id
> - quota_date
> - create_at
> - create_by
> - update_at
> - update_by


## Table :: schedule_doctor
> - id (schedule_id)
> - hospital_code
> - poli_code
> - doctor_id
> - day
> - time
> - quota
> - status
> - create_at
> - create_by
> - update_at
> - update_by

## Table :: ms_hospital
> - code (hospital_code)
> - name
> - address
> - postal_code
> - remark
> - create_at
> - create_by
> - update_at
> - update_by

|code|name|address|phone|email|remark|
|:---|:---|:---|:---|:---|:---|
|RS001|Rumah Sakit An Nisa|Jl. Gatot Subroto Km.3 No.96 Cibodas Kota Tangerang - Banten|(021) 552 5564|marketing@rsannisa.co.id|remark|

## Table :: ms_policlinic
> - code (poli_Code)
> - name
> - remark
> - create_at
> - create_by
> - update_at
> - update_by

|code|name|
|:---|:---|
|PK000|Poliklinik Mata|
|PK001|Poliklinik Bedah|
|PK002|Poliklinik Anak|
|PK003|Poliklinik Umum|
|PK004|Poliklinik Gigi|
|PK005|Poliklinik Tulang|

## Table :: ms_doctor
> - id (doctor_id)
> - fullname
> - gender
> - place
> - university
> - qualified
> - idi_number
> - str_number
> - sip_number
> - archive_number
> - establish_date
> - expired_date
> - region
> - status
> - remark
> - create_at
> - create_by
> - update_at
> - update_by



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


## Table :: ms_guarantor_connection
> - code
> - title
> - remark
> - create_at
> - create_by
> - update_at
> - update_by

|code|title|
|:---|:---|
|ORG|Orang Tua|
|SDR|Saudara|
|ANK|Anak|
|SPS|Pasangan|
|MDR|Mandiri|


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
