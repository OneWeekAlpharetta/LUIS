# LUIS
Assets related to LUIS (Language Understanding Intelligent Service)

This project uses LUIS to determine the intent for the bot.  Several intents are included:
1) for Health Care
2) for Child Care
3) HELP!  
4) "None" -- a default intent included in all apps, and kept by ours

We also used features to create exchangeable entities for "healthcare provider" and "childcare provider";  these features are enumerated in the code, but may be extended.

In cases where the engine was misclassifying intent, we hardcoded the phrase into the correct intent.
