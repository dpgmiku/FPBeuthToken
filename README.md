# FPBeuthToken
  
  
## TODO 
- erweitern: getAdvert(): "schlaue" Wahl eines Adverts
- owner und balanceOf[owner] (Hauptkonto) voneinander trennen, sonst Probleme nach transferOwnership(...)
- was machen mit leeren Werbungen in der Hashmap?
- (implementieren: advertId zu "richtiger" eindeutigen ID machen?)



erledigt:

- implementieren: Liste/HashMap für die User (address, balance)
- implementieren: getCoinCount() const returns (uint coinCount) {}
- implementieren: buyAdvert(string url) payable {}
- implementieren: getAdvertValue(string url) const returns (uint value) {}
- implementieren: buyGood(uint value) returns (bool success){}
- Umbenennen: investorBalance -> balanceOf
- Andere Typen: advert -> (uniqueId => Advertisement)
- Funktion: buyGood(...): +Gutschrift auf Hauptkonto
- Neues Attribut: Advertisement: +id
- Funktion: getAdvertValue(...): Advert-id erhalten, dann prüfen ob Advert dem msg.sender gehört, value returnen
- implementieren: Liste/HashMap für die Investoren/Werbung (fromAddress, advertUrl, value)
- implementieren: charge(uint percentCharged, string advertWatched) {}
- implementieren: getAdvert() const returns (string advertUrl) {}


