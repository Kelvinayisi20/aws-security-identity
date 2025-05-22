# aws-security-identity
How I Created the IAM Policy
I logged into the AWS Management Console and navigated to IAM → Policies → Create policy.

I selected the Visual editor tab to create the policy without writing JSON.

I named the policy kelvinayisi_59 to match my IAM username for easy tracking.

Using the visual editor, I chose the AWS services and specific actions I wanted to allow.

For example, I selected read-only actions for S3 like ListBucket and GetObject.

I specified the resources the policy applies to (like all buckets or specific ones).

After reviewing, I saved the policy.

2. How I Attached the Policy to the User
I went to IAM → Users, and selected my user account, kelvinayisi_59.

Under the Permissions tab, I clicked Add permissions.

I chose Attach existing policies directly.

I searched for and selected the policy I had created called kelvinayisi_59.

Finally, I attached this policy to my user.

3. How I Tested Access
I logged into the AWS Console as the user kelvinayisi_59. (Shown in Screenshot 1)

I tested the permissions by trying to access allowed AWS services and actions.

Screenshot 2 shows that I was able to successfully perform permitted actions, confirming the policy works as intended.

4. Summary
I created a custom IAM policy named kelvinayisi_59 using the visual editor.

I attached the policy to my IAM user with the same name.

I tested and verified that the permissions are working correctly.
