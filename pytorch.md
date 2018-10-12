# PyTorch

## [model serialization](https://github.com/pytorch/pytorch/blob/761d6799beb3afa03657a71776412a2171ee7533/docs/source/notes/serialization.rst)

- saving model parameters

```python
torch.save(the_model.state_dict(), PATH)
```

- loading model parameters

```python
the_model = TheModelClass(*args, **kwargs)
the_model.load_state_dict(torch.load(PATH))
```

- saving the entire model

```python
torch.save(the_model, PATH)
```

- loading an entire model

```python
the_model = torch.load(PATH)
```