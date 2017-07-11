# deregister-asgs-of-elb

Deregister the ASGs of a selected ELB.

## Role Variables

* `elb`      : Dictionary storing information of the Elastic Load Balancer
  * `name`   : Elastic Load Balancer name
  * `region` : Elastic Load Balancer region

## Example playbook

```yaml
- hosts: localhost
  connection   : local
  gather_facts : no
  roles:
    - deregister-asgs-of-elb
```

## License

GPLv2

## Author Information
jamatute (jamatute@paradigmadigital.com)
