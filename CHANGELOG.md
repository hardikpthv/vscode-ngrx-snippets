<a name="9.0.0"></a>

## 9.0.0 (2020-07-04)

* Updated documentation [`README.md`](https://github.com/hardikpthv/vscode-ngrx-snippets/blob/master/README.md) for new snippets
* Updated Typescript snippets for:
  * `ngrx-effect-setup` -> make use of `createEffect`
  * `ngrx-effect` -> make use of `createEffect`
  * `ngrx-reducer-setup` -> make use of `createReducer`  
* Added Typescript snippets for:
  * `createAction` to create actions
    * `ngrx-create-action-setup`
    * `ngrx-create-action`
    * `ngrx-create-action-props`
  * `ngrx-root-effect-registration` to register effect in root module
  * `ngrx-feat-effect-registration` to register effect in feature module
  * `createReducer` to create reducers
    * `ngrx-reducer`
    * `ngrx-on` -> make use of `on`
  * `StoreDevtoolsModule.instrument` configuration
  * `createEntityAdapter` to create entity adapter 
    * `ngrx-entity-adapter-setup`
  * `EntityMetadataMap` to setup entities
    * `ngrx-entities-setup`
    * `ngrx-entity-store-registration` to register entity store
  * `ngrx-entity-data-service` to create data service using `tEntityCollectionServiceBase`, `tEntityCollectionServiceElementsFactory` and other utility methods.

<a name="0.4.0"></a>

## 0.4.0 (2019-12-24)

* Fixed `ofType` moved into `pipe` ([afc31d9](https://github.com/hardikpthv/vscode-ngrx-snippets/pull/2/commits/afc31d9dc0c826bac4760f74e9a6ae29b49d1b46))

<a name="0.3.2"></a>

## 0.3.2 (2018-05-30)

* Fixed typo in snippet ([3d4d28f](https://github.com/hardikpthv/vscode-ngrx-snippets/pull/1/commits/3d4d28f110a92c86e86fd1a30729095d97691ce7))

<a name="0.3.1"></a>

## 0.3.1 (2018-09-08)

* Fixed reducer snippet alignment

<a name="0.3.0"></a>

## 0.3.0 (2018-09-08)

* Fixed TypeScript snippets for
  * Action constants and creators
  * Reducers
  * Effects 
  * Store Selector
    * `createSelector` and `createFeatureSelector`

<a name="0.2.0"></a>

## 0.2.0 (2018-09-08)

- Updated config.

<a name="0.0.1"></a>

## 0.0.1 (2018-09-08)

- Initial release
