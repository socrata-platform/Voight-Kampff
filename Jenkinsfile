@Library('socrata-pipeline-library@11.2.0')

commonPipeline(
    jobName: 'voight_kampff',
    languageOptions: [
        ruby: [
            version: '2.7.7',
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
