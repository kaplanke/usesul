# usesul


send mail from bash via sendgrid
---

mailx -s "$SUBJECT" -S smtp="smtp://smtp.sendgrid.net:587" -S smtp-auth=login -S smtp-auth-user=apikey -S smtp-auth-password=<apikey> -S from="from@mail.adress"  "someone@somewhere.com" 
