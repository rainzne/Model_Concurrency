# Model_Concurrency

Comment installer : Installer uppaal

Comment tester : dans la section vérifieur de uppaal j'ai crée 4 propriète qui test du coup notre algo : 
E<> Client1.GotTicket  -> pour savoir si 
E<> Client1.GotServiceTicket
E<> Client1.Granted
A[] Client1.Granted imply HasServiceTicket
