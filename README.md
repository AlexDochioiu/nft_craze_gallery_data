# NFT Craze - Gallery

## Collections Data

To include your project and/or collections, please modify the `collections.json` file and then raise a PR. The new data should follow the pattern:
```json
{
    "project": "My Cool Company",
    "collections": [
        {
            "logoUrl": "https://raw.githubusercontent.com/AlexDochioiu/nft_craze_gallery_data/main/logos/first_collection.jpeg",
            "collectionName": "First Collection",
            "policies": [
              "1132301ad4b3cb7deaddzc8f03f77189082a5738c0167e1772233097",
              "12c131301adj2b7d5addbc8f03f77189082a5738c0167e1772233h32"
            ]
        },
        {
            "logoUrl": "https://raw.githubusercontent.com/AlexDochioiu/nft_craze_gallery_data/main/logos/second_collection.jpeg",
            "collectionName": "Second Collection",
            "policies": [
              "1131301ad4b3cb7deaddbc8f03f77189082a5738c0167e1772233097"
            ]
        }
    ]
}
```
* To speed up the PR process, please add in the description the cardanoscan url for the minting transaction and/or any other proof that your policies are indeed the original ones for the project (needed to weed out fake NFT copies).
* For the collection image, you can either point directly to an external url or upload a picture on this repo and point to it. If your image is ipfs hosted, please put the url from a public gateway, such as `ipfs.blockfrost.dev/ipfs/...`
* If you launch extra collections at a later stage, feel free to come back and include them in your project's json structure.

## Buy us a coffee
*Any donnations to support this project (NFTs and/or ADA) are welcomed at the address:*
addr1qxqz9xuzaznul542599u8a6wyp3lss54k62c95kwgqsatefgh2vkhtv4pcy82r78swe77ynkwdqx0pprf5uyy6espywsdacvzy
