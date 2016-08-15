# Stanford NLP demo

## Build and Deploy

1. Start the JBoss EAP server

        $EAP7_HOME/bin/standalone.sh

1. build and deploy the archive:

        mvn clean install wildfly:deploy

## Try run

    http://localhost:8080/nerdemo/api/v1/classify/Microsoft%20SCCM%20Windows%20Server%202012%20Web%20Development%20Expert%20(SME3)%20at%20PSI%20Pax%20(Baltimore,%20MD)


## References

[Day 14: Stanford NER–How To Setup Your Own Name, Entity, and Recognition Server in the Cloud](https://blog.openshift.com/day-14-stanford-ner-how-to-setup-your-own-name-entity-and-recognition-server-in-the-cloud/)
