# ipp5-frontend-launcher

~~~~~ sh
npm install e53e04ac/ipp5-frontend-launcher
~~~~~

~~~~~ mjs
import { Ipp5FrontendLauncher } from 'ipp5-frontend-launcher';
~~~~~

~~~~~ mermaid
graph RL;
  A["package.json\npackage-lock.json"];
  subgraph "dependencies";
    B_0(["azure-terraformer"]);
    B_1(["event-emitter"]);
    B_2(["file-entry-native"]);
    B_3(["hold"]);
    B_4(["ipp5-types"]);
  end;
  subgraph "devDependencies";
    B_5(["@types/node"]);
    B_6(["file-entry"]);
  end;
  subgraph "github";
    C_0(["e53e04ac/azure-terraformer\nb192a6b3fb5efd1f7a188f53b3878ee310f8cd51"]);
    C_1(["e53e04ac/event-emitter\ndb90659b1c25a4e17e8a8dbf8920a630fd30321d"]);
    C_2(["e53e04ac/file-entry-native\n26c4ace9610606e884be3c2af2bf69fe10662193"]);
    C_3(["e53e04ac/hold\n472cfb85bada328cba9c6faddcf45b1241761027"]);
    C_4(["e53e04ac/ipp5-types\nb7903575f37345c3c5ff26b19d03d94c743efd9d"]);
    C_6(["e53e04ac/file-entry\n4ff5464c0df35db0fc552346c4011d115ebb4cde"]);
  end;
  subgraph "npmjs";
    C_5(["@types/node\n18.14.6"]);
  end;
  A ----> B_0;
  A ----> B_1;
  A ----> B_2;
  A ----> B_3;
  A ----> B_4;
  A ----> B_5;
  A ----> B_6;
  B_0 ----> C_0;
  B_1 ----> C_1;
  B_2 ----> C_2;
  B_3 ----> C_3;
  B_4 ----> C_4;
  B_5 ----> C_5;
  B_6 ----> C_6;
  click C_0 "https://github.com/e53e04ac/azure-terraformer/tree/b192a6b3fb5efd1f7a188f53b3878ee310f8cd51";
  click C_1 "https://github.com/e53e04ac/event-emitter/tree/db90659b1c25a4e17e8a8dbf8920a630fd30321d";
  click C_2 "https://github.com/e53e04ac/file-entry-native/tree/26c4ace9610606e884be3c2af2bf69fe10662193";
  click C_3 "https://github.com/e53e04ac/hold/tree/472cfb85bada328cba9c6faddcf45b1241761027";
  click C_4 "https://github.com/e53e04ac/ipp5-types/tree/b7903575f37345c3c5ff26b19d03d94c743efd9d";
  click C_5 "https://www.npmjs.com/package/@types/node/v/18.14.6";
  click C_6 "https://github.com/e53e04ac/file-entry/tree/4ff5464c0df35db0fc552346c4011d115ebb4cde";
~~~~~

~~~~~ mermaid
graph RL;
  subgraph "e53e04ac/ipp5-frontend-launcher";
    E_0(["namespace Ipp5FrontendLauncher"]);
    E_1(["type Ipp5FrontendLauncher"]);
    E_2(["const Ipp5FrontendLauncher"]);
  end;
  M["index.d.ts"]
  subgraph "azure-terraformer";
    I_0_0(["AzureTerraformer"]);
  end;
  subgraph "event-emitter";
    I_1_0(["EventEmitter"]);
  end;
  subgraph "file-entry";
    I_2_0(["FileEntry"]);
  end;
  subgraph "hold";
    I_3_0(["Get"]);
    I_3_1(["ValueOrGet"]);
  end;
  subgraph "ipp5-types";
    I_4_0(["Ipp5FrontendEnvMap"]);
  end;
  M ----> I_0_0;
  M ----> I_1_0;
  M ----> I_2_0;
  M ----> I_3_0;
  M ----> I_3_1;
  M ----> I_4_0;
  E_0 ----> M;
  E_1 ----> M;
  E_2 ----> M;
~~~~~

~~~~~ mermaid
graph RL;
  subgraph "e53e04ac/ipp5-frontend-launcher";
    E_0(["Ipp5FrontendLauncher"]);
  end;
  M["index.mjs"]
  subgraph "azure-terraformer";
    I_0_0(["AzureTerraformer"]);
  end;
  subgraph "event-emitter";
    I_1_0(["EventEmitter"]);
  end;
  subgraph "file-entry-native";
    I_2_0(["FileEntry"]);
  end;
  subgraph "hold";
    I_3_0(["hold"]);
    I_3_1(["unwrap"]);
  end;
  M ----> I_0_0;
  M ----> I_1_0;
  M ----> I_2_0;
  M ----> I_3_0;
  M ----> I_3_1;
  E_0 ----> M;
~~~~~
