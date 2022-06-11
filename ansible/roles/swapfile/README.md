# Swapfile

Create or remove a swapfile.

## Requirements

None.

## Role Variables

```yml
swapfile_state: 'present'
```

This variable controls if the swap file is created and mounted (`present`) or disabled and removed (`'absent'`).

```yml
swapfile_path: '/swapfile'
```
Path to the swap file.

```yml
swapfile_size: '4G'
```
Size of the swap file.

## Dependencies

None.

## Example Playbook

Enable swap

```yml
- hosts: all

  roles:
    - role: swapfile
      vars:
        swapfile_size: '2G'
```

Disable swap

```yml
- hosts: all

  roles:
    - role: swapfile
      vars:
        swapfile_state: 'absent'
```

## License

MIT
