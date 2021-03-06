[![star this repo](http://githubbadges.com/star.svg?user=nakosung&repo=UnrealDarknet&style=default)](https://github.com/nakosung/UnrealDarknet)
[![fork this repo](http://githubbadges.com/fork.svg?user=nakosung&repo=UnrealDarknet&style=default)](https://github.com/nakosung/UnrealDarknet/fork) 
# UnrealDarknet

- [Darknet](http://pjreddie.com/darknet/) on UnrealEngine.
- Powered by [Unreal.js](https://github.com/ncsoft/Unreal.js)

```js
let net = DarknetNetwork.parse_network_cfg(cfgfile)
net.load_weights(weightfile)
const input_size = net.get_network_input_size()
let input = DarknetMatrix.make(1,input_size)
...
```

- rnn.js, yolo.js is working! :)
```
< car 0.008212059986596465 0.11794955815587727 0.2582981142462516 0.7473386653832027 0.876048103278997
< diningtable 0.0037762266622333174 0.11794955815587727 0.2582981142462516 0.7473386653832027 0.876048103278997
< horse 0.01571061588740985 0.11794955815587727 0.2582981142462516 0.7473386653832027 0.876048103278997
< motorbike 0.22114932313654379 0.11794955815587727 0.2582981142462516 0.7473386653832027 0.876048103278997
< pottedplant 0.17379721077381305 0.11794955815587727 0.2582981142462516 0.7473386653832027 0.876048103278997
< sheep 0.013608549189502828 0.11794955815587727 0.2582981142462516 0.7473386653832027 0.876048103278997
```

![Imgur](http://i.imgur.com/dTRPc4A.png)

## Installation guide
- Clone this repo and update sub-modules
- Build darknet first
- Download pretrained weights from [darknet homepage](http://pjreddie.com/darknet/)
