# Spring CLI Command To Add Tanzu Application Platform Files

## Installation

Install the [Spring CLI](https://spring-projects-experimental.github.io/spring-cli/spring-cli/installation.html)

Run `$ spring command add https://github.com/ryanjbaxter/tap-command-for-spring-cli`

## Usage

To see all parameters run `$ spring help tap init`

## Sample

`$ spring tap init --name movies --workload-type web --git-url https://github.com/ryanjbaxter/movies --git-branch main --source-image gcr.io/cf-sandbox-rbaxter/tap-bootcamp/build-service/movies --local-path ./ --namespace dev-namespace --workload-yaml-path ./workload.yaml`