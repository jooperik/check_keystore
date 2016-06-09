# check_keystore
Check certificates inside a java keystore

Modified script from David Gouveia - https://www.davidgouveia.net/2013/07/simple-script-to-check-expiry-dates-on-a-java-keystore-jks-file/

Usage:
  ./check_keystore -k|--keystore <keystore> [-t|--threshold <threshold>] [-a|--all]

  Parameters:
  *  -k|--keystore     Path to keystore.
  *  -t|--treshold     Defines how many days before the certificate expires WARNING status appears.
  *  -a|--all          Will show status for each certificate including Alias, Serial Number and expiration day.
