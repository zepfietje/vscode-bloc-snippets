[![Visual Studio Marketplace Version](https://img.shields.io/visual-studio-marketplace/v/zepfietje.bloc-snippets)](https://marketplace.visualstudio.com/items?itemName=zepfietje.bloc-snippets)
[![Visual Studio Marketplace Installs - Azure DevOps Extension](https://img.shields.io/visual-studio-marketplace/azure-devops/installs/total/zepfietje.bloc-snippets)](https://marketplace.visualstudio.com/items?itemName=zepfietje.bloc-snippets)
[![Starware](https://img.shields.io/badge/Starware-⭐-black?labelColor=f9b00d)](https://github.com/zepfietje/starware)

# VS Code Bloc Snippets

This Visual Studio Code extension contains Dart snippets for the [Bloc](https://github.com/felangel/bloc) state management library.

## Installation

Install this extension from the [Visual Studio Marketplace](https://marketplace.visualstudio.com/items?itemName=zepfietje.bloc-snippets) or the command line.

```console
$ code --install-extension zepfietje.bloc-snippets
```

## Usage

| Trigger                 | Description                               |
| ----------------------- | ----------------------------------------- |
| blocprovider            | `BlocProvider` widget                     |
| multiblocprovider       | `MultiBlocProvider` widget                |
| repositoryprovider      | `RepositoryProvider` widget               |
| multirepositoryprovider | `MultiRepositoryProvider` widget          |
| blocbuilder             | `BlocBuilder` widget                      |
| bloclistener            | `BlocListener` widget                     |
| multibloclistener       | `MultiBlocListener` widget                |
| blocconsumer            | `BlocConsumer` widget                     |
| bloc                    | `context<SubjectBloc>.bloc()`             |
| repository              | `context.repository<SubjectRepository>()` |
| blocobserver            | `BlocObserver` class                      |
| blocstate               | `SubjectVerbState` class                  |
| blocstateinitial        | `SubjectInitial` class                    |
| blocstateinprogress     | `SubjectVerbInProgress` class             |
| blocstatesuccess        | `SubjectVerbSuccess` class                |
| blocstatefailure        | `SubjectVerbFailure` class                |
| blocevent               | `SubjectNounVerb` class                   |
| bloceventstarted        | `SubjectStarted` class                    |

## Starware

VS Code Bloc Snippets is Starware.  
This means you're free to use the project, as long as you star its GitHub repository.  
Your appreciation makes us grow and glow up. ⭐
