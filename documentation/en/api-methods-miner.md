# Groups
* [](#)
  * [Closing](#Closing)
  * [Session](#Session)
  * [Shutdown](#Shutdown)
  * [Version](#Version)
* [Actor](#Actor)
  * [ActorAddress](#ActorAddress)
  * [ActorSectorSize](#ActorSectorSize)
* [Auth](#Auth)
  * [AuthNew](#AuthNew)
  * [AuthVerify](#AuthVerify)
* [Create](#Create)
  * [CreateBackup](#CreateBackup)
* [Deals](#Deals)
  * [DealsConsiderOfflineRetrievalDeals](#DealsConsiderOfflineRetrievalDeals)
  * [DealsConsiderOfflineStorageDeals](#DealsConsiderOfflineStorageDeals)
  * [DealsConsiderOnlineRetrievalDeals](#DealsConsiderOnlineRetrievalDeals)
  * [DealsConsiderOnlineStorageDeals](#DealsConsiderOnlineStorageDeals)
  * [DealsImportData](#DealsImportData)
  * [DealsList](#DealsList)
  * [DealsPieceCidBlocklist](#DealsPieceCidBlocklist)
  * [DealsSetConsiderOfflineRetrievalDeals](#DealsSetConsiderOfflineRetrievalDeals)
  * [DealsSetConsiderOfflineStorageDeals](#DealsSetConsiderOfflineStorageDeals)
  * [DealsSetConsiderOnlineRetrievalDeals](#DealsSetConsiderOnlineRetrievalDeals)
  * [DealsSetConsiderOnlineStorageDeals](#DealsSetConsiderOnlineStorageDeals)
  * [DealsSetPieceCidBlocklist](#DealsSetPieceCidBlocklist)
* [I](#I)
  * [ID](#ID)
* [Log](#Log)
  * [LogList](#LogList)
  * [LogSetLevel](#LogSetLevel)
* [Market](#Market)
  * [MarketCancelDataTransfer](#MarketCancelDataTransfer)
  * [MarketDataTransferUpdates](#MarketDataTransferUpdates)
  * [MarketGetAsk](#MarketGetAsk)
  * [MarketGetDealUpdates](#MarketGetDealUpdates)
  * [MarketGetRetrievalAsk](#MarketGetRetrievalAsk)
  * [MarketImportDealData](#MarketImportDealData)
  * [MarketListDataTransfers](#MarketListDataTransfers)
  * [MarketListDeals](#MarketListDeals)
  * [MarketListIncompleteDeals](#MarketListIncompleteDeals)
  * [MarketListRetrievalDeals](#MarketListRetrievalDeals)
  * [MarketRestartDataTransfer](#MarketRestartDataTransfer)
  * [MarketSetAsk](#MarketSetAsk)
  * [MarketSetRetrievalAsk](#MarketSetRetrievalAsk)
* [Mining](#Mining)
  * [MiningBase](#MiningBase)
* [Net](#Net)
  * [NetAddrsListen](#NetAddrsListen)
  * [NetAgentVersion](#NetAgentVersion)
  * [NetAutoNatStatus](#NetAutoNatStatus)
  * [NetBandwidthStats](#NetBandwidthStats)
  * [NetBandwidthStatsByPeer](#NetBandwidthStatsByPeer)
  * [NetBandwidthStatsByProtocol](#NetBandwidthStatsByProtocol)
  * [NetConnect](#NetConnect)
  * [NetConnectedness](#NetConnectedness)
  * [NetDisconnect](#NetDisconnect)
  * [NetFindPeer](#NetFindPeer)
  * [NetPeers](#NetPeers)
  * [NetPubsubScores](#NetPubsubScores)
* [Pieces](#Pieces)
  * [PiecesGetCIDInfo](#PiecesGetCIDInfo)
  * [PiecesGetPieceInfo](#PiecesGetPieceInfo)
  * [PiecesListCidInfos](#PiecesListCidInfos)
  * [PiecesListPieces](#PiecesListPieces)
* [Pledge](#Pledge)
  * [PledgeSector](#PledgeSector)
* [Return](#Return)
  * [ReturnAddPiece](#ReturnAddPiece)
  * [ReturnFetch](#ReturnFetch)
  * [ReturnFinalizeSector](#ReturnFinalizeSector)
  * [ReturnMoveStorage](#ReturnMoveStorage)
  * [ReturnReadPiece](#ReturnReadPiece)
  * [ReturnReleaseUnsealed](#ReturnReleaseUnsealed)
  * [ReturnSealCommit1](#ReturnSealCommit1)
  * [ReturnSealCommit2](#ReturnSealCommit2)
  * [ReturnSealPreCommit1](#ReturnSealPreCommit1)
  * [ReturnSealPreCommit2](#ReturnSealPreCommit2)
  * [ReturnUnsealPiece](#ReturnUnsealPiece)
* [Sealing](#Sealing)
  * [SealingAbort](#SealingAbort)
  * [SealingSchedDiag](#SealingSchedDiag)
* [Sector](#Sector)
  * [SectorGetExpectedSealDuration](#SectorGetExpectedSealDuration)
  * [SectorGetSealDelay](#SectorGetSealDelay)
  * [SectorMarkForUpgrade](#SectorMarkForUpgrade)
  * [SectorRemove](#SectorRemove)
  * [SectorSetExpectedSealDuration](#SectorSetExpectedSealDuration)
  * [SectorSetSealDelay](#SectorSetSealDelay)
  * [SectorStartSealing](#SectorStartSealing)
* [Sectors](#Sectors)
  * [SectorsList](#SectorsList)
  * [SectorsRefs](#SectorsRefs)
  * [SectorsStatus](#SectorsStatus)
  * [SectorsUpdate](#SectorsUpdate)
* [Storage](#Storage)
  * [StorageAddLocal](#StorageAddLocal)
  * [StorageAttach](#StorageAttach)
  * [StorageBestAlloc](#StorageBestAlloc)
  * [StorageDeclareSector](#StorageDeclareSector)
  * [StorageDropSector](#StorageDropSector)
  * [StorageFindSector](#StorageFindSector)
  * [StorageInfo](#StorageInfo)
  * [StorageList](#StorageList)
  * [StorageLocal](#StorageLocal)
  * [StorageLock](#StorageLock)
  * [StorageReportHealth](#StorageReportHealth)
  * [StorageStat](#StorageStat)
  * [StorageTryLock](#StorageTryLock)
* [Worker](#Worker)
  * [WorkerConnect](#WorkerConnect)
  * [WorkerJobs](#WorkerJobs)
  * [WorkerStats](#WorkerStats)
## 


### Closing


Perms: read

Inputs: `null`

Response: `{}`

### Session


Perms: read

Inputs: `null`

Response: `"07070707-0707-0707-0707-070707070707"`

### Shutdown


Perms: admin

Inputs: `null`

Response: `{}`

### Version


Perms: read

Inputs: `null`

Response:
```json
{
  "Version": "string value",
  "APIVersion": 65536,
  "BlockDelay": 42
}
```

## Actor


### ActorAddress
There are not yet any comments for this method.

Perms: read

Inputs: `null`

Response: `"f01234"`

### ActorSectorSize
There are not yet any comments for this method.

Perms: read

Inputs:
```json
[
  "f01234"
]
```

Response: `34359738368`

## Auth


### AuthNew


Perms: admin

Inputs:
```json
[
  null
]
```

Response: `"Ynl0ZSBhcnJheQ=="`

### AuthVerify


Perms: read

Inputs:
```json
[
  "string value"
]
```

Response: `null`

## Create


### CreateBackup
CreateBackup creates node backup onder the specified file name. The
method requires that the lotus-miner is running with the
LOTUS_BACKUP_BASE_PATH environment variable set to some path, and that
the path specified when calling CreateBackup is within the base path


Perms: admin

Inputs:
```json
[
  "string value"
]
```

Response: `{}`

## Deals


### DealsConsiderOfflineRetrievalDeals
There are not yet any comments for this method.

Perms: read

Inputs: `null`

Response: `true`

### DealsConsiderOfflineStorageDeals
There are not yet any comments for this method.

Perms: read

Inputs: `null`

Response: `true`

### DealsConsiderOnlineRetrievalDeals
There are not yet any comments for this method.

Perms: read

Inputs: `null`

Response: `true`

### DealsConsiderOnlineStorageDeals
There are not yet any comments for this method.

Perms: read

Inputs: `null`

Response: `true`

### DealsImportData
There are not yet any comments for this method.

Perms: write

Inputs:
```json
[
  {
    "/": "bafy2bzacea3wsdh6y3a36tb3skempjoxqpuyompjbmfeyf34fi3uy6uue42v4"
  },
  "string value"
]
```

Response: `{}`

### DealsList
There are not yet any comments for this method.

Perms: read

Inputs: `null`

Response: `null`

### DealsPieceCidBlocklist
There are not yet any comments for this method.

Perms: read

Inputs: `null`

Response: `null`

### DealsSetConsiderOfflineRetrievalDeals
There are not yet any comments for this method.

Perms: admin

Inputs:
```json
[
  true
]
```

Response: `{}`

### DealsSetConsiderOfflineStorageDeals
There are not yet any comments for this method.

Perms: admin

Inputs:
```json
[
  true
]
```

Response: `{}`

### DealsSetConsiderOnlineRetrievalDeals
There are not yet any comments for this method.

Perms: admin

Inputs:
```json
[
  true
]
```

Response: `{}`

### DealsSetConsiderOnlineStorageDeals
There are not yet any comments for this method.

Perms: admin

Inputs:
```json
[
  true
]
```

Response: `{}`

### DealsSetPieceCidBlocklist
There are not yet any comments for this method.

Perms: admin

Inputs:
```json
[
  null
]
```

Response: `{}`

## I


### ID


Perms: read

Inputs: `null`

Response: `"12D3KooWGzxzKZYveHXtpG6AsrUJBcWxHBFS2HsEoGTxrMLvKXtf"`

## Log


### LogList


Perms: write

Inputs: `null`

Response: `null`

### LogSetLevel


Perms: write

Inputs:
```json
[
  "string value",
  "string value"
]
```

Response: `{}`

## Market


### MarketCancelDataTransfer
ClientCancelDataTransfer cancels a data transfer with the given transfer ID and other peer


Perms: read

Inputs:
```json
[
  3,
  "12D3KooWGzxzKZYveHXtpG6AsrUJBcWxHBFS2HsEoGTxrMLvKXtf",
  true
]
```

Response: `{}`

### MarketDataTransferUpdates
There are not yet any comments for this method.

Perms: write

Inputs: `null`

Response:
```json
{
  "TransferID": 3,
  "Status": 1,
  "BaseCID": {
    "/": "bafy2bzacea3wsdh6y3a36tb3skempjoxqpuyompjbmfeyf34fi3uy6uue42v4"
  },
  "IsInitiator": true,
  "IsSender": true,
  "Voucher": "string value",
  "Message": "string value",
  "OtherPeer": "12D3KooWGzxzKZYveHXtpG6AsrUJBcWxHBFS2HsEoGTxrMLvKXtf",
  "Transferred": 42
}
```

### MarketGetAsk
There are not yet any comments for this method.

Perms: read

Inputs: `null`

Response:
```json
{
  "Ask": {
    "Price": "0",
    "VerifiedPrice": "0",
    "MinPieceSize": 1032,
    "MaxPieceSize": 1032,
    "Miner": "f01234",
    "Timestamp": 10101,
    "Expiry": 10101,
    "SeqNo": 42
  },
  "Signature": {
    "Type": 2,
    "Data": "Ynl0ZSBhcnJheQ=="
  }
}
```

### MarketGetDealUpdates
There are not yet any comments for this method.

Perms: read

Inputs: `null`

Response:
```json
{
  "Proposal": {
    "PieceCID": {
      "/": "bafy2bzacea3wsdh6y3a36tb3skempjoxqpuyompjbmfeyf34fi3uy6uue42v4"
    },
    "PieceSize": 1032,
    "VerifiedDeal": true,
    "Client": "f01234",
    "Provider": "f01234",
    "Label": "string value",
    "StartEpoch": 10101,
    "EndEpoch": 10101,
    "StoragePricePerEpoch": "0",
    "ProviderCollateral": "0",
    "ClientCollateral": "0"
  },
  "ClientSignature": {
    "Type": 2,
    "Data": "Ynl0ZSBhcnJheQ=="
  },
  "ProposalCid": {
    "/": "bafy2bzacea3wsdh6y3a36tb3skempjoxqpuyompjbmfeyf34fi3uy6uue42v4"
  },
  "AddFundsCid": null,
  "PublishCid": null,
  "Miner": "12D3KooWGzxzKZYveHXtpG6AsrUJBcWxHBFS2HsEoGTxrMLvKXtf",
  "Client": "12D3KooWGzxzKZYveHXtpG6AsrUJBcWxHBFS2HsEoGTxrMLvKXtf",
  "State": 42,
  "PiecePath": ".lotusminer/fstmp123",
  "MetadataPath": ".lotusminer/fstmp123",
  "SlashEpoch": 10101,
  "FastRetrieval": true,
  "Message": "string value",
  "StoreID": 12,
  "FundsReserved": "0",
  "Ref": {
    "TransferType": "string value",
    "Root": {
      "/": "bafy2bzacea3wsdh6y3a36tb3skempjoxqpuyompjbmfeyf34fi3uy6uue42v4"
    },
    "PieceCid": null,
    "PieceSize": 1024
  },
  "AvailableForRetrieval": true,
  "DealID": 5432,
  "CreationTime": "0001-01-01T00:00:00Z",
  "TransferChannelId": {
    "Initiator": "12D3KooWGzxzKZYveHXtpG6AsrUJBcWxHBFS2HsEoGTxrMLvKXtf",
    "Responder": "12D3KooWGzxzKZYveHXtpG6AsrUJBcWxHBFS2HsEoGTxrMLvKXtf",
    "ID": 3
  }
}
```

### MarketGetRetrievalAsk
There are not yet any comments for this method.

Perms: read

Inputs: `null`

Response:
```json
{
  "PricePerByte": "0",
  "UnsealPrice": "0",
  "PaymentInterval": 42,
  "PaymentIntervalIncrease": 42
}
```

### MarketImportDealData
There are not yet any comments for this method.

Perms: write

Inputs:
```json
[
  {
    "/": "bafy2bzacea3wsdh6y3a36tb3skempjoxqpuyompjbmfeyf34fi3uy6uue42v4"
  },
  "string value"
]
```

Response: `{}`

### MarketListDataTransfers
There are not yet any comments for this method.

Perms: write

Inputs: `null`

Response: `null`

### MarketListDeals
There are not yet any comments for this method.

Perms: read

Inputs: `null`

Response: `null`

### MarketListIncompleteDeals
There are not yet any comments for this method.

Perms: read

Inputs: `null`

Response: `null`

### MarketListRetrievalDeals
There are not yet any comments for this method.

Perms: read

Inputs: `null`

Response: `null`

### MarketRestartDataTransfer
MinerRestartDataTransfer attempts to restart a data transfer with the given transfer ID and other peer


Perms: read

Inputs:
```json
[
  3,
  "12D3KooWGzxzKZYveHXtpG6AsrUJBcWxHBFS2HsEoGTxrMLvKXtf",
  true
]
```

Response: `{}`

### MarketSetAsk
There are not yet any comments for this method.

Perms: admin

Inputs:
```json
[
  "0",
  "0",
  10101,
  1032,
  1032
]
```

Response: `{}`

### MarketSetRetrievalAsk
There are not yet any comments for this method.

Perms: admin

Inputs:
```json
[
  {
    "PricePerByte": "0",
    "UnsealPrice": "0",
    "PaymentInterval": 42,
    "PaymentIntervalIncrease": 42
  }
]
```

Response: `{}`

## Mining


### MiningBase
There are not yet any comments for this method.

Perms: read

Inputs: `null`

Response:
```json
{
  "Cids": null,
  "Blocks": null,
  "Height": 0
}
```

## Net


### NetAddrsListen


Perms: read

Inputs: `null`

Response:
```json
{
  "Addrs": null,
  "ID": "12D3KooWGzxzKZYveHXtpG6AsrUJBcWxHBFS2HsEoGTxrMLvKXtf"
}
```

### NetAgentVersion


Perms: read

Inputs:
```json
[
  "12D3KooWGzxzKZYveHXtpG6AsrUJBcWxHBFS2HsEoGTxrMLvKXtf"
]
```

Response: `"string value"`

### NetAutoNatStatus


Perms: read

Inputs: `null`

Response:
```json
{
  "Reachability": 1,
  "PublicAddr": "string value"
}
```

### NetBandwidthStats


Perms: read

Inputs: `null`

Response:
```json
{
  "TotalIn": 9,
  "TotalOut": 9,
  "RateIn": 12.3,
  "RateOut": 12.3
}
```

### NetBandwidthStatsByPeer


Perms: read

Inputs: `null`

Response:
```json
{
  "12D3KooWSXmXLJmBR1M7i9RW9GQPNUhZSzXKzxDHWtAgNuJAbyEJ": {
    "TotalIn": 174000,
    "TotalOut": 12500,
    "RateIn": 100,
    "RateOut": 50
  }
}
```

### NetBandwidthStatsByProtocol


Perms: read

Inputs: `null`

Response:
```json
{
  "/fil/hello/1.0.0": {
    "TotalIn": 174000,
    "TotalOut": 12500,
    "RateIn": 100,
    "RateOut": 50
  }
}
```

### NetConnect


Perms: write

Inputs:
```json
[
  {
    "Addrs": null,
    "ID": "12D3KooWGzxzKZYveHXtpG6AsrUJBcWxHBFS2HsEoGTxrMLvKXtf"
  }
]
```

Response: `{}`

### NetConnectedness


Perms: read

Inputs:
```json
[
  "12D3KooWGzxzKZYveHXtpG6AsrUJBcWxHBFS2HsEoGTxrMLvKXtf"
]
```

Response: `1`

### NetDisconnect


Perms: write

Inputs:
```json
[
  "12D3KooWGzxzKZYveHXtpG6AsrUJBcWxHBFS2HsEoGTxrMLvKXtf"
]
```

Response: `{}`

### NetFindPeer


Perms: read

Inputs:
```json
[
  "12D3KooWGzxzKZYveHXtpG6AsrUJBcWxHBFS2HsEoGTxrMLvKXtf"
]
```

Response:
```json
{
  "Addrs": null,
  "ID": "12D3KooWGzxzKZYveHXtpG6AsrUJBcWxHBFS2HsEoGTxrMLvKXtf"
}
```

### NetPeers


Perms: read

Inputs: `null`

Response: `null`

### NetPubsubScores


Perms: read

Inputs: `null`

Response: `null`

## Pieces


### PiecesGetCIDInfo
There are not yet any comments for this method.

Perms: read

Inputs:
```json
[
  {
    "/": "bafy2bzacea3wsdh6y3a36tb3skempjoxqpuyompjbmfeyf34fi3uy6uue42v4"
  }
]
```

Response:
```json
{
  "CID": {
    "/": "bafy2bzacea3wsdh6y3a36tb3skempjoxqpuyompjbmfeyf34fi3uy6uue42v4"
  },
  "PieceBlockLocations": null
}
```

### PiecesGetPieceInfo
There are not yet any comments for this method.

Perms: read

Inputs:
```json
[
  {
    "/": "bafy2bzacea3wsdh6y3a36tb3skempjoxqpuyompjbmfeyf34fi3uy6uue42v4"
  }
]
```

Response:
```json
{
  "PieceCID": {
    "/": "bafy2bzacea3wsdh6y3a36tb3skempjoxqpuyompjbmfeyf34fi3uy6uue42v4"
  },
  "Deals": null
}
```

### PiecesListCidInfos
There are not yet any comments for this method.

Perms: read

Inputs: `null`

Response: `null`

### PiecesListPieces
There are not yet any comments for this method.

Perms: read

Inputs: `null`

Response: `null`

## Pledge


### PledgeSector
Temp api for testing


Perms: write

Inputs: `null`

Response: `{}`

## Return


### ReturnAddPiece


Perms: admin

Inputs:
```json
[
  {
    "Sector": {
      "Miner": 1000,
      "Number": 9
    },
    "ID": "07070707-0707-0707-0707-070707070707"
  },
  {
    "Size": 1032,
    "PieceCID": {
      "/": "bafy2bzacea3wsdh6y3a36tb3skempjoxqpuyompjbmfeyf34fi3uy6uue42v4"
    }
  },
  {
    "Code": 0,
    "Message": "string value"
  }
]
```

Response: `{}`

### ReturnFetch


Perms: admin

Inputs:
```json
[
  {
    "Sector": {
      "Miner": 1000,
      "Number": 9
    },
    "ID": "07070707-0707-0707-0707-070707070707"
  },
  {
    "Code": 0,
    "Message": "string value"
  }
]
```

Response: `{}`

### ReturnFinalizeSector


Perms: admin

Inputs:
```json
[
  {
    "Sector": {
      "Miner": 1000,
      "Number": 9
    },
    "ID": "07070707-0707-0707-0707-070707070707"
  },
  {
    "Code": 0,
    "Message": "string value"
  }
]
```

Response: `{}`

### ReturnMoveStorage


Perms: admin

Inputs:
```json
[
  {
    "Sector": {
      "Miner": 1000,
      "Number": 9
    },
    "ID": "07070707-0707-0707-0707-070707070707"
  },
  {
    "Code": 0,
    "Message": "string value"
  }
]
```

Response: `{}`

### ReturnReadPiece


Perms: admin

Inputs:
```json
[
  {
    "Sector": {
      "Miner": 1000,
      "Number": 9
    },
    "ID": "07070707-0707-0707-0707-070707070707"
  },
  true,
  {
    "Code": 0,
    "Message": "string value"
  }
]
```

Response: `{}`

### ReturnReleaseUnsealed


Perms: admin

Inputs:
```json
[
  {
    "Sector": {
      "Miner": 1000,
      "Number": 9
    },
    "ID": "07070707-0707-0707-0707-070707070707"
  },
  {
    "Code": 0,
    "Message": "string value"
  }
]
```

Response: `{}`

### ReturnSealCommit1


Perms: admin

Inputs:
```json
[
  {
    "Sector": {
      "Miner": 1000,
      "Number": 9
    },
    "ID": "07070707-0707-0707-0707-070707070707"
  },
  null,
  {
    "Code": 0,
    "Message": "string value"
  }
]
```

Response: `{}`

### ReturnSealCommit2


Perms: admin

Inputs:
```json
[
  {
    "Sector": {
      "Miner": 1000,
      "Number": 9
    },
    "ID": "07070707-0707-0707-0707-070707070707"
  },
  null,
  {
    "Code": 0,
    "Message": "string value"
  }
]
```

Response: `{}`

### ReturnSealPreCommit1


Perms: admin

Inputs:
```json
[
  {
    "Sector": {
      "Miner": 1000,
      "Number": 9
    },
    "ID": "07070707-0707-0707-0707-070707070707"
  },
  null,
  {
    "Code": 0,
    "Message": "string value"
  }
]
```

Response: `{}`

### ReturnSealPreCommit2


Perms: admin

Inputs:
```json
[
  {
    "Sector": {
      "Miner": 1000,
      "Number": 9
    },
    "ID": "07070707-0707-0707-0707-070707070707"
  },
  {
    "Unsealed": {
      "/": "bafy2bzacea3wsdh6y3a36tb3skempjoxqpuyompjbmfeyf34fi3uy6uue42v4"
    },
    "Sealed": {
      "/": "bafy2bzacea3wsdh6y3a36tb3skempjoxqpuyompjbmfeyf34fi3uy6uue42v4"
    }
  },
  {
    "Code": 0,
    "Message": "string value"
  }
]
```

Response: `{}`

### ReturnUnsealPiece


Perms: admin

Inputs:
```json
[
  {
    "Sector": {
      "Miner": 1000,
      "Number": 9
    },
    "ID": "07070707-0707-0707-0707-070707070707"
  },
  {
    "Code": 0,
    "Message": "string value"
  }
]
```

Response: `{}`

## Sealing


### SealingAbort
There are not yet any comments for this method.

Perms: admin

Inputs:
```json
[
  {
    "Sector": {
      "Miner": 1000,
      "Number": 9
    },
    "ID": "07070707-0707-0707-0707-070707070707"
  }
]
```

Response: `{}`

### SealingSchedDiag
SealingSchedDiag dumps internal sealing scheduler state


Perms: admin

Inputs:
```json
[
  true
]
```

Response: `{}`

## Sector


### SectorGetExpectedSealDuration
SectorGetExpectedSealDuration gets the expected time for a sector to seal


Perms: read

Inputs: `null`

Response: `60000000000`

### SectorGetSealDelay
SectorGetSealDelay gets the time that a newly-created sector
waits for more deals before it starts sealing


Perms: read

Inputs: `null`

Response: `60000000000`

### SectorMarkForUpgrade
There are not yet any comments for this method.

Perms: admin

Inputs:
```json
[
  9
]
```

Response: `{}`

### SectorRemove
There are not yet any comments for this method.

Perms: admin

Inputs:
```json
[
  9
]
```

Response: `{}`

### SectorSetExpectedSealDuration
SectorSetExpectedSealDuration sets the expected time for a sector to seal


Perms: write

Inputs:
```json
[
  60000000000
]
```

Response: `{}`

### SectorSetSealDelay
SectorSetSealDelay sets the time that a newly-created sector
waits for more deals before it starts sealing


Perms: write

Inputs:
```json
[
  60000000000
]
```

Response: `{}`

### SectorStartSealing
SectorStartSealing can be called on sectors in Empty or WaitDeals states
to trigger sealing early


Perms: write

Inputs:
```json
[
  9
]
```

Response: `{}`

## Sectors


### SectorsList
List all staged sectors


Perms: read

Inputs: `null`

Response: `null`

### SectorsRefs
There are not yet any comments for this method.

Perms: read

Inputs: `null`

Response:
```json
{
  "98000": [
    {
      "SectorID": 100,
      "Offset": 10485760,
      "Size": 1048576
    }
  ]
}
```

### SectorsStatus
Get the status of a given sector by ID


Perms: read

Inputs:
```json
[
  9,
  true
]
```

Response:
```json
{
  "SectorID": 9,
  "State": "Proving",
  "CommD": null,
  "CommR": null,
  "Proof": "Ynl0ZSBhcnJheQ==",
  "Deals": null,
  "Ticket": {
    "Value": null,
    "Epoch": 10101
  },
  "Seed": {
    "Value": null,
    "Epoch": 10101
  },
  "PreCommitMsg": null,
  "CommitMsg": null,
  "Retries": 42,
  "ToUpgrade": true,
  "LastErr": "string value",
  "Log": null,
  "SealProof": 8,
  "Activation": 10101,
  "Expiration": 10101,
  "DealWeight": "0",
  "VerifiedDealWeight": "0",
  "InitialPledge": "0",
  "OnTime": 10101,
  "Early": 10101
}
```

### SectorsUpdate
There are not yet any comments for this method.

Perms: admin

Inputs:
```json
[
  9,
  "Proving"
]
```

Response: `{}`

## Storage


### StorageAddLocal
There are not yet any comments for this method.

Perms: admin

Inputs:
```json
[
  "string value"
]
```

Response: `{}`

### StorageAttach


Perms: admin

Inputs:
```json
[
  {
    "ID": "76f1988b-ef30-4d7e-b3ec-9a627f4ba5a8",
    "URLs": null,
    "Weight": 42,
    "CanSeal": true,
    "CanStore": true
  },
  {
    "Capacity": 9,
    "Available": 9,
    "Reserved": 9
  }
]
```

Response: `{}`

### StorageBestAlloc


Perms: admin

Inputs:
```json
[
  1,
  34359738368,
  "sealing"
]
```

Response: `null`

### StorageDeclareSector


Perms: admin

Inputs:
```json
[
  "76f1988b-ef30-4d7e-b3ec-9a627f4ba5a8",
  {
    "Miner": 1000,
    "Number": 9
  },
  1,
  true
]
```

Response: `{}`

### StorageDropSector


Perms: admin

Inputs:
```json
[
  "76f1988b-ef30-4d7e-b3ec-9a627f4ba5a8",
  {
    "Miner": 1000,
    "Number": 9
  },
  1
]
```

Response: `{}`

### StorageFindSector


Perms: admin

Inputs:
```json
[
  {
    "Miner": 1000,
    "Number": 9
  },
  1,
  34359738368,
  true
]
```

Response: `null`

### StorageInfo


Perms: admin

Inputs:
```json
[
  "76f1988b-ef30-4d7e-b3ec-9a627f4ba5a8"
]
```

Response:
```json
{
  "ID": "76f1988b-ef30-4d7e-b3ec-9a627f4ba5a8",
  "URLs": null,
  "Weight": 42,
  "CanSeal": true,
  "CanStore": true
}
```

### StorageList
There are not yet any comments for this method.

Perms: admin

Inputs: `null`

Response:
```json
{
  "76f1988b-ef30-4d7e-b3ec-9a627f4ba5a8": [
    {
      "Miner": 1000,
      "Number": 100,
      "SectorFileType": 2
    }
  ]
}
```

### StorageLocal
There are not yet any comments for this method.

Perms: admin

Inputs: `null`

Response:
```json
{
  "76f1988b-ef30-4d7e-b3ec-9a627f4ba5a8": "/data/path"
}
```

### StorageLock


Perms: admin

Inputs:
```json
[
  {
    "Miner": 1000,
    "Number": 9
  },
  1,
  1
]
```

Response: `{}`

### StorageReportHealth


Perms: admin

Inputs:
```json
[
  "76f1988b-ef30-4d7e-b3ec-9a627f4ba5a8",
  {
    "Stat": {
      "Capacity": 9,
      "Available": 9,
      "Reserved": 9
    },
    "Err": "string value"
  }
]
```

Response: `{}`

### StorageStat
There are not yet any comments for this method.

Perms: admin

Inputs:
```json
[
  "76f1988b-ef30-4d7e-b3ec-9a627f4ba5a8"
]
```

Response:
```json
{
  "Capacity": 9,
  "Available": 9,
  "Reserved": 9
}
```

### StorageTryLock


Perms: admin

Inputs:
```json
[
  {
    "Miner": 1000,
    "Number": 9
  },
  1,
  1
]
```

Response: `true`

## Worker


### WorkerConnect
WorkerConnect tells the node to connect to workers RPC


Perms: admin

Inputs:
```json
[
  "string value"
]
```

Response: `{}`

### WorkerJobs
There are not yet any comments for this method.

Perms: admin

Inputs: `null`

Response:
```json
{
  "ef8d99a2-6865-4189-8ffa-9fef0f806eee": [
    {
      "ID": {
        "Sector": {
          "Miner": 1000,
          "Number": 100
        },
        "ID": "76081ba0-61bd-45a5-bc08-af05f1c26e5d"
      },
      "Sector": {
        "Miner": 1000,
        "Number": 100
      },
      "Task": "seal/v0/precommit/2",
      "RunWait": 0,
      "Start": "2020-11-12T09:22:07Z",
      "Hostname": "host"
    }
  ]
}
```

### WorkerStats
There are not yet any comments for this method.

Perms: admin

Inputs: `null`

Response:
```json
{
  "ef8d99a2-6865-4189-8ffa-9fef0f806eee": {
    "Info": {
      "Hostname": "host",
      "Resources": {
        "MemPhysical": 274877906944,
        "MemSwap": 128849018880,
        "MemReserved": 2147483648,
        "CPUs": 64,
        "GPUs": [
          "aGPU 1337"
        ]
      }
    },
    "Enabled": true,
    "MemUsedMin": 0,
    "MemUsedMax": 0,
    "GpuUsed": false,
    "CpuUse": 0
  }
}
```
