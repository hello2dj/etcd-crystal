etcd1: etcd --name etcd1 --listen-client-urls https://localhost:4001 --advertise-client-urls https://localhost:4001 --listen-peer-urls https://localhost:7001 --initial-advertise-peer-urls https://localhost:7001 --initial-cluster-token etcd-cluster-1 --initial-cluster 'etcd1=https://localhost:7001,etcd2=https://localhost:7002,etcd3=https://localhost:7003' --initial-cluster-state new --cert-file=spec/data/certs/server.pem --key-file=spec/data/certs/server-key.pem --peer-cert-file=spec/data/certs/server.pem --peer-key-file=spec/data/certs/server-key.pem --peer-client-cert-auth --peer-trusted-ca-file=spec/data/certs/ca.pem --data-dir=tmp/server01
etcd2: etcd --name etcd2 --listen-client-urls https://localhost:4002 --advertise-client-urls https://localhost:4002 --listen-peer-urls https://localhost:7002 --initial-advertise-peer-urls https://localhost:7002 --initial-cluster-token etcd-cluster-1 --initial-cluster 'etcd1=https://localhost:7001,etcd2=https://localhost:7002,etcd3=https://localhost:7003' --initial-cluster-state new --cert-file=spec/data/certs/server.pem --key-file=spec/data/certs/server-key.pem --peer-cert-file=spec/data/certs/server.pem --peer-key-file=spec/data/certs/server-key.pem --peer-client-cert-auth --peer-trusted-ca-file=spec/data/certs/ca.pem --data-dir=tmp/server02
etcd3: etcd --name etcd3 --listen-client-urls https://localhost:4003 --advertise-client-urls https://localhost:4003 --listen-peer-urls https://localhost:7003 --initial-advertise-peer-urls https://localhost:7003 --initial-cluster-token etcd-cluster-1 --initial-cluster 'etcd1=https://localhost:7001,etcd2=https://localhost:7002,etcd3=https://localhost:7003' --initial-cluster-state new --cert-file=spec/data/certs/server.pem --key-file=spec/data/certs/server-key.pem --peer-cert-file=spec/data/certs/server.pem --peer-key-file=spec/data/certs/server-key.pem --peer-client-cert-auth --peer-trusted-ca-file=spec/data/certs/ca.pem --data-dir=tmp/server03
