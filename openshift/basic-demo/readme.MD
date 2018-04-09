Here are the variables needed to run the playbook:

ansible-playbook ./playbook.yml \
-e student_id=demo \
-e rhn_username=yourusername \
-e rhn_password=yourpassword \
-e rhn_pool=yourpool \
-e aws_openshift_key=yourkey \
-e aws_openshift_secret=yoursecret \
-e ha=false \
-e num_instances=2 \
-e cns_storage=true \
-e dnz_zone=yourdnszone

Make sure you have your AWS system vars setup
