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
    C_0(["e53e04ac/azure-terraformer\nf6669b7616fd464bc62a1eab31640210a24a3d19"]);
    C_1(["e53e04ac/event-emitter\nfe89a990ada06652bfffee75818dff0445762cd1"]);
    C_2(["e53e04ac/file-entry-native\n8cf50e81fe937ed0d787537f04ed0e5518950c90"]);
    C_3(["e53e04ac/hold\n8575e49e6bfe80ba61782e3a8f9eb80f78776713"]);
    C_4(["e53e04ac/ipp5-types\ndd9746113b508ee3f68a7a75b5f8d7e6910dd7c7"]);
    C_6(["e53e04ac/file-entry\n5562ecc181baea1a9b666fd9490bfabd2c155d30"]);
  end;
  subgraph "npmjs";
    C_5(["@types/node\n18.14.5"]);
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
  click C_0 "https://github.com/e53e04ac/azure-terraformer/tree/f6669b7616fd464bc62a1eab31640210a24a3d19";
  click C_1 "https://github.com/e53e04ac/event-emitter/tree/fe89a990ada06652bfffee75818dff0445762cd1";
  click C_2 "https://github.com/e53e04ac/file-entry-native/tree/8cf50e81fe937ed0d787537f04ed0e5518950c90";
  click C_3 "https://github.com/e53e04ac/hold/tree/8575e49e6bfe80ba61782e3a8f9eb80f78776713";
  click C_4 "https://github.com/e53e04ac/ipp5-types/tree/dd9746113b508ee3f68a7a75b5f8d7e6910dd7c7";
  click C_5 "https://www.npmjs.com/package/@types/node/v/18.14.5";
  click C_6 "https://github.com/e53e04ac/file-entry/tree/5562ecc181baea1a9b666fd9490bfabd2c155d30";
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
