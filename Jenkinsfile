@Library('socrata-pipeline-library@10.2.1') _

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
        ]
    ],
    teamsChannelWebhookId: 'WORKFLOW_EVENTING_AUTOMATION',
)
