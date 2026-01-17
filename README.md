# INFO
Il codice è proviene da [YouTube API](https://developers.google.com/youtube/v3/guides/uploading_a_video?hl=it) è stato rimodernizzato per essere adattato alle ultime versioni di python ma lasciato con tutti gli argomenti base (descritti nel link precedente).
# Librerie
per le installare le librerie è sufficiente eseguire il comando:
```
pip install -r requirements.txt
```
# File obbligatori
Per garantire il funzionamento, come approfondito anche nel link sopra riportato, è richiesto il file client_secrets.json che contiene tutte le info per usare OAuth 2.0 con la API di YouTube. Per creare questo file è utile utilizzare la [Google API Console](https://console.developers.google.com/?hl=it).  Esempio file richiesto risultante:
```
{
    "installed": {
        "client_id": "xxxx.apps.googleusercontent.com",
        "project_id": "xxxx",
        "auth_uri": "https://accounts.google.com/o/oauth2/auth",
        "token_uri": "https://oauth2.googleapis.com/token",
        "auth_provider_x509_cert_url": "https://www.googleapis.com/oauth2/v1/certs",
        "client_secret": "xxxx",
        "redirect_uris": []
    }
}
```
