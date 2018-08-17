# readmes
Populates ASTA's database with READMEs of most popular Github repos

Make sure there is a category 'Github READMEs.' Note the companyId which contains this category and hard-code into addArticle in dbhelpers.js.

Add a config file:

module.exports = {
 DBNAME: '',
 DBUSERNAME: '',
 DBPASSWORD: '',
 DBHOST: '',
 DBPORT: ,
 apiKey: ''
};

To adjust the number of readmes added to the database, change stars parameter in url GET request to github in readmes.js.
