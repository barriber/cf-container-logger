# cf-container-logger
# required environment variables:
    # FIREBASE_AUTH_URL - the main firebase ref to authenticate on initialization
    # FIREBASE_SECRET - the secret key to write to the firebase auth url and all future derived urls
    # LOGGER_ID - logger id. if a container will include this id in its label, we will log it
    # LOG_TO_CONSOLE - by default, logging to console is disabled and only logging to a file is enabled. set this env to log to console to