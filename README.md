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
    C_0(["e53e04ac/azure-terraformer\nfedeeba769ef8e68213a742b67e2d43b6de32bc8"]);
    C_1(["e53e04ac/event-emitter\n63f34d0c90cbecf2b424b38c0615e67fd7ba6594"]);
    C_2(["e53e04ac/file-entry-native\n6abbcd40e32dcd6a941bf0400da1b5fcb2d15839"]);
    C_3(["e53e04ac/hold\n050a2db413598fe87670b5b6bd34b804776a3657"]);
    C_4(["e53e04ac/ipp5-types\n77007f82947cc0eb20ebd9c346c7ee980eb41787"]);
    C_6(["e53e04ac/file-entry\n9379ee74366b97ba20ce7a5cd4f3107b68848365"]);
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
  click C_0 "https://github.com/e53e04ac/azure-terraformer/tree/fedeeba769ef8e68213a742b67e2d43b6de32bc8";
  click C_1 "https://github.com/e53e04ac/event-emitter/tree/63f34d0c90cbecf2b424b38c0615e67fd7ba6594";
  click C_2 "https://github.com/e53e04ac/file-entry-native/tree/6abbcd40e32dcd6a941bf0400da1b5fcb2d15839";
  click C_3 "https://github.com/e53e04ac/hold/tree/050a2db413598fe87670b5b6bd34b804776a3657";
  click C_4 "https://github.com/e53e04ac/ipp5-types/tree/77007f82947cc0eb20ebd9c346c7ee980eb41787";
  click C_5 "https://www.npmjs.com/package/@types/node/v/18.14.6";
  click C_6 "https://github.com/e53e04ac/file-entry/tree/9379ee74366b97ba20ce7a5cd4f3107b68848365";
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
