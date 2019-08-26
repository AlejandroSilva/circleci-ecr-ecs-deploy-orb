este repositorio sirve de

        version: 2.1


circleci namespace create asilva github AlejandroSilva
circleci orb create asilva/ecr-ecs-deploy
circleci orb validate <path> [flags]

circleci orb publish config.yml asilva/ecr-ecs-deploy@0.0.1