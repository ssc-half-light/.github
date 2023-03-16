# hermes [![Netlify Status](https://api.netlify.com/api/v1/badges/f66ada49-9361-4e73-abee-1d538e3b59a3/deploy-status)](https://app.netlify.com/sites/ssc-hermes/deploys)

<div>
    <img style="width: 15vw" src="./hermes_logo_edit.png" alt="Hermes logo"
        title="Hermes logo"
    >
</div>

## Private by default social networking
At a high level this is like *Signal*, the messaging app, in the sense that no one is able to read your messages except the recipients, not even the server.

This project is designed to share images via a social network. It started with using services that are more traditional — a DB and blob host, + UCANs for ID.

But, [wnfs](https://guide.fission.codes/developers/webnative/file-system-wnfs) already has a way to do read permissions on a per-user basis, so we can e2e encrypt *everything*. It's kind of interesting because it's all based on decryption capabilities instead of access control.

-----------------

The social part is all configurable too, at a pretty granular level. So you can configure things like -- do you want to let your friends see who your other friends are? Or hide that info from everyone? In any case, you *get to choose* who can read that. Not even the server-operator is able to read that info, unless you allow them to.

This is a big difference from traditional social networks, like *Instagram*, where the server reads/knows all your data.


## relevant links

[join the discord server](https://discord.gg/SxWNsDMxT4)
