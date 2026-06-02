@Library('socrata-pipeline-library@11.2.0') _

commonPipeline(
    jobName: 'voight_kampff',
    languageOptions: [
        ruby: [
            version: '3.4.7',
        ],
    ],
    projects: [
        [
            name: 'voight_kampff',
            language: 'ruby',
            paths: [
                buildContext: '.',
                versionFile: 'VERSION',
            ],
            type: 'library',
            publishToTylerArtifactory: true,
        ]
    ],
    teamsChannelWebhookId: 'WORKFLOW_EVENTING_AUTOMATION',
)
