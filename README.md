# AWS Security and Identity Assignment

## Steps taken

#### Created two S3 buckets 
*prod-object* and *dev-env-object*

#### Created IAM user 
*intern-ade* 

#### Created a policy called 
*intern-policy*,_prod-object_: `list only policy`; _dev-env-object_ `delete bucket,delete object and list bucket policy`.

#### Created a IAM user group namely, 
*intern2026*

### Used the poicy simulator to test the Policies

- Intern-ade can view the *prod-object S3 bucket, he cannot alter it, while he can view, delete object, delete the bucket of the dev-env-object.

- Intern-ade cannot create a bucket.

- Screenshot are in the directory.

*_Adepegba Isaiah_*
