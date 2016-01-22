# mailanalyzer
Mail Analyzer GLPI Plugin may be used to combine CC mails into one Ticket

It is currently tested with GLPI 0.83.8

Must be copied into *glpifolder*/plugins/mailanalyzer

To be installed and enabled via the plugins configuration page in GLPI.

It creates a new table in the DB with the purpose of storing email guid (generated by email servers) in order to be able (if possible) to match emails in mailgate which have been sent using 'CC' and 'Reply to all'.

  This solves the problem of duplicated Tickets when an email is sent to GLPI and CC to others. and when those CC uses 'Reply to All', GLPI by default will create a new ticket. See: http://glpi.userecho.com/topic/1090667-new-rule-criteria-for-mail-receivers/
  
  
  


