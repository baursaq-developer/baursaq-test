# baursaq-test
mails:
employee1@mg.baursaq.com
employee2@mg.baursaq.com
app.config['API_SECRET'] = os.environ.get('BAURSAQ_API_SECRET', 'baursaq123')
app.config['API_ISS'] = 'baursaq-api'
app.config['API_AUD'] = 'baursaq-clients'
app.config['API_TOKEN_EXPIRES_MINUTES'] = 30
